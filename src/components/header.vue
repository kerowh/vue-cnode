<template>
    <div class="header">
      <router-link  :to="{name:'root'}">
        <img src="../assets/cnodejs_light.svg" alt="">
      </router-link>
<!--      <ul>-->
<!--        <li><a href="#">首页</a></li>-->
<!--        <li><a href="#">登陆</a></li>-->
<!--        <li><a href="#">API</a></li>-->
<!--        <li><a href="#">关于</a></li>-->
<!--        <li><a href="#">注册</a></li>-->
<!--        <li><a href="#">登陆</a></li>-->
<!--      </ul>-->
    </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  .header{
    background-color:#5a5555;
    height: 50px;
    position: relative;
  }
  img{
    max-width: 120px;
    /*margin-left: 50px;*/
    margin-top: 10px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
  }
  ul{
    /*去掉默认的样式*/
    list-style: none;
    float: right;
    margin: 4px;
  }
  li{
    /*转换成行内元素*/
    display: inline-block;
    padding: 10px 15px;
  }
  a{
    text-decoration: none;
    color:#cccccc;
    font-size: 14px;
    text-shadow: none;
  }
</style>
