<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <router-view name="main"></router-view>
    </div>
  </div>
</template>

<script>
import Header from './components/header'
import PostList from './components/PostList'
import Article from './components/Article'
export default {
  name: 'App',
  components: {
    Header,
    PostList,
    Article
  }
}
</script>

<style>
.main{
  width: 80%;
  margin: 0 auto;
}
  #app{
    background-color: #e1e1e1;
  }
</style>
