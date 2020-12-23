<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">


      <!-- start main menu -->
       <MainMenu />
        <!-- end main menu -->

            <!-- start breadcrumb -->
         <nav class="breadcrumb">
            <ul>
                <li>
                    <nuxt-link to="/">کتاب ها</nuxt-link>
                </li>
                <li class="is-active">
                    <nuxt-link to="/newBook">کتاب جدید</nuxt-link>
                </li>
            </ul>
         </nav>

      </div>
    </section>
    
  </div>
</template>

<script>
import MainMenu from '@/components/MainMenu.vue'

export default {
  components:{
    MainMenu
  },
  head(){
    return{
      title: ''
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
