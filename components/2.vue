<template>
  <div id="app">
    <el-row>
  <el-col :span="24"><div class="grid-content bg-purple-dark">
    <span class="sp">设置封面</span>
     <el-button class="bt1" plain>退出</el-button>
    </div></el-col>
</el-row>

<el-button class="but1" style="background: #36f007" type="primary">设置封面</el-button>
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
 
  .but1{
     display: block;
    width: 9.75rem;
    
    margin: 25rem auto;
  }
  .sp{
    
    margin-right: 10rem
  }
  .bt1{
    height: 2rem;
    line-height: 2.rem;
   
  }
</style>
