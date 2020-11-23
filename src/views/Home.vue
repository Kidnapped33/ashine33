<template>
  <div class="home">
   <header>
    <Nav/>
   </header>
   <main>跑马灯</main>
   <Footer/>
  </div>
</template>

<script>
import Nav from '@/components/nav.vue'
import Footer from '@/components/footer.vue'
export default {
components:{Nav,Footer}

}


</script>
<style lang='scss' scoped>
$red:red;

.home{
  min-height:100vh;
  display: flex;
  flex-direction: column;

  >.main{
  
  flex-grow:1;
}
}




main{
  border: 1px solid red;
  // display: flex;
  flex-grow: 1;
}


  
</style>