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

         <!-- start form -->
         <form>
             <div class="field">
                 <label class="label">عنوان</label>
                 <div class="control">
                   <input type="text" class="input is-large" placeholder="مثال" required>
                 </div>
             </div>

             <div class="columns is-desktop">

               <div class="column">
                 <label class="label">قیمت</label>
                 <div class="control has-icons-left">
                   <input type="number" class="input" placeholder="22.000" required>
                   <span class="icon is-small is-left">
                     <i class="fa fa-dollar-sign"></i>
                   </span>
                 </div>
               </div>

               <div class="column">
                 <label class="label">تعداد صفحات</label>
                 <input type="number" class="input" placeholder="270" required>
               </div>

               <div class="column">
                 <label class="label">ISBN</label>
                 <div class="control">
                   <input type="text" class="input" placeholder="12-3456-78-9">
                 </div>
               </div>

             </div>
         </form>

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
      title: 'کتاب جدید'
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
