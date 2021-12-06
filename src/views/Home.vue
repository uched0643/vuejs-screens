<template>
  <div class="home h-full overflow-hidden">
    <Header/>
    <div class="main-section-container overflow-hidden">
      <div class="main-container h-full w-full bg-white">
      <div class="left-side-nav" v-if="toggleSidenav">
           <LeftSidebar/>
      </div>
      <div class="main-section-container    ">
        <Tabs/>
        <div class="rounded">
        <Main />
        </div>
      </div>
      <div class="right-side-nav  ">
        <RightSidebar/>
      </div>
      </div>
    </div>
 
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Header from '@/components/Header.vue'
import LeftSidebar from '@/components/left-sidebar.vue';
import RightSidebar from '@/components/right-sidebar.vue';
import Main from '@/components/main.vue';
import Tabs from '@/components/tabs.vue';

@Options({
  components: {
    Header,LeftSidebar,RightSidebar, Main,Tabs
  },
})
export default class Home extends Vue {
  toggleSidenav:boolean = true
}
</script>
<style lang="scss">
.main-container{
  display: flex;
  .left-side-nav, .right-side-nav {
    width: 40%;
  }
   
}
  @media screen and (max-width:1030px) {
    .right-side-nav{
      width: 0%; display: none;
    }
    .left-side-nav{
      width:60%;
    }
    
  }
   @media screen and (max-width:800px) {
    .left-side-nav{
     width: 0%; display: none;
    }
}
</style>
