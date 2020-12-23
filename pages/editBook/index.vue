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
                    <nuxt-link to="/newBook">ویرایش کتاب</nuxt-link>
                </li>
            </ul>
         </nav>
         <!-- end breadcrumb -->


         <!-- start form -->
         <form>
             <div class="field">
                 <label class="label">عنوان</label>
                 <div class="control">
                   <input type="text" class="input is-large" placeholder="مثال" value="راز" required>
                 </div>
             </div>

             <div class="columns is-desktop">

               <div class="column">
                 <label class="label">قیمت</label>
                 <div class="control has-icons-left">
                   <input type="number" class="input" placeholder="22.000" value="22.000" required>
                   <span class="icon is-small is-left">
                     <i class="fa fa-dollar-sign"></i>
                   </span>
                 </div>
               </div>

               <div class="column">
                 <label class="label">تعداد صفحات</label>
                 <input type="number" class="input" placeholder="270" value="270" required>
               </div>

               <div class="column">
                 <label class="label">ISBN</label>
                 <div class="control">
                   <input type="text" class="input" placeholder="12-3456-78-9" value="12-3456-78-9">
                 </div>
               </div>

             </div>

             <div class="field">
               <label class="label">جلد کتاب</label>
               <div class="control">
                   <img src="images/raz.jpg" alt="">
               </div>
               <div class="control">
                 <div class="file has-name">
                   <label class="file-label">
                     <input type="file" class="file-input">
                     <span class="file-cta">
                       <span class="file-icon">
                         <i class="fa fa-upload"></i>
                       </span>
                       <span class="file-label">
                         انتخاب جلد
                       </span>
                     </span>
                   </label>
                 </div>
               </div>
             </div>

            <div class="field">
              <div class="buttons">
                <button class="button is-medium is-success">ویرایش کتاب</button>
                <button class="button is-medium is-light">لغو</button>
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
      title: 'ویرایش کتاب'
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
