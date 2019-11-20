<!--
 * @Author: your name
 * @Date: 2019-11-13 11:14:23
 * @LastEditTime: 2019-11-15 11:40:17
 * @LastEditors: 马川
 * @Description: In User Settings Edit
 * @FilePath: \third-staged:\ruanjian\work\meituanwaimai\src\pages\ZujianPage.vue
 -->
<template>
  <div class="boxdasmd">
    <Zujian></Zujian>
    <Footer></Footer>
  </div>
</template>
<script>
import Zujian from '../components/Zujian';
import Footer from '../components/Footer';

export default {
  name: 'ZujianPage',
  data () {
    return {
    }
  },
  components:{
    Zujian,Footer
  }
}
</script>
 
<style scoped>


</style>