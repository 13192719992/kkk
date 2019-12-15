<template>
  <div id="app">
    <el-row>
  <el-col :span="24"><div class="grid-content bg-purple-dark">登录</div></el-col>
</el-row>
<img src="./tx.png" alt="">
<el-input class="inp1" v-model="input" placeholder="请输入内容"></el-input>
<el-button class="but1" type="primary">主要按钮</el-button>
  </div>
</template>

<script>
// export default {
//   name: 'App'
   

// }

</script>

<style>
*{
  margin: 0;
  padding: 0;
}
 .bg-purple-dark {
    background: #36f007;
  }
   .grid-content {
     width: 100%;
     color: white;
    min-height: 3.5rem;
    text-align: center;
    line-height: 3.5rem;
    font-size: 2.0rem
  }
  img{
    display: block;
    margin: 4.75rem auto;
  }
  .inp1{
    display: block;
    width: 9.75rem;
    margin: 1.25rem auto;
  }
  .but1{
     display: block;
    width: 9.75rem;
    background-color: #36f007;
    margin: .75rem auto;
  }
</style>
