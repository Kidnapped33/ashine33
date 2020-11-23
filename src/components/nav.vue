<template>
<div class="nav">
<div class="logo el-icon-s-home"></div>
   <div>
   <a href="">首页</a>
   | 
   <a href=""> vue作品</a> 
   | 
   <a href="">js作品</a>
   </div>
   <div>
  <el-container> 
  <el-input  class="input" v-model="input" placeholder="请输入内容"></el-input>
    <el-button type="primary">搜索</el-button>
  login
  </el-container>
  </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
$red:red;
.nav{
    border: 1px solid $red;
    padding: 5px 20%;
    display:flex;
    justify-content: space-between;
    align-items: center;

    @media (max-width:800px){
     padding: 5px;
}
}



.el-input{
  width: 200px;
  height: 40px;
  margin-right:1px;
}
</style>