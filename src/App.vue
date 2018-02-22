<template>
  <div id="App">
    <Banner></Banner>
    <Properties></Properties>
    <AboutUs></AboutUs>
    <CostList></CostList>
    <NeedHelp></NeedHelp>
    <FooterDiv></FooterDiv>
    <CopyWrite></CopyWrite>
  </div>

</template>

<script>
 import AboutUs from '../src/components/AboutUs.vue'
  import Banner from '../src/components/Banner.vue'
 import CopyWrite from '../src/components/CopyWrite.vue'
 import CostList from '../src/components/CostList.vue'
 import FooterDiv from '../src/components/FooterDiv.vue'
 import NeedHelp from '../src/components/NeedHelp.vue'
 import Properties from '../src/components/Properties.vue'
export default {
     components:{
       AboutUs,
       Banner,
       CopyWrite,
       CostList,
       FooterDiv,
       NeedHelp,
       Properties,

     },
  data () {
    return {

    }
  },
  name: 'App'
}
</script>
<style >

  body {
    font-family: iransans, sans-serif !important;
    direction: rtl;
    background-color: #f2f2f2 !important;
    color: #212529;
    text-align: right;
    background-color: rgba(242, 242, 242, 1);
  }
</style>
