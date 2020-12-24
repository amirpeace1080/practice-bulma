<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">


      <!-- start main menu -->
       <MainMenu />
        <!-- end main menu -->

        <div class="column">
            <nav class="breadcrumb">
                <ul>
                    <li>
                        <nuxt-link to="/orders">سفارشات</nuxt-link>
                    </li>
                    <li class="is-active">
                        <nuxt-link to="">ویرایش سفارش</nuxt-link>
                    </li>
                </ul>
            </nav>

            <h1 class="subtitle is-3">
                <span class="has-text-grey-light">سفارش <strong>44204-3</strong></span>
            </h1>

            <div class="columns is-desktop">

                <div class="column is-4-desktop">
                    <!-- ستون سمت چپ , برای اطلاعات سفارش -->
                    <p class="heading">
                        <strong>تاریخ</strong>
                    </p>
                    <p class="content">2020/12/23</p>
                    <p class="heading">
                        <strong>وضعیت</strong>
                    </p>

                    <div class="buttons">
                        <button class="button is-small is-warning">در حال پردازش</button>
                        <button class="button is-small is-success is-outlined">موفقیت آمیز</button>
                        <button class="button is-small is-danger is-outlined">خطا</button>
                    </div>

                    <p class="heading">
                        <strong>مشتری</strong>
                    </p>
                    <p class="content">
                        <strong>
                            <nuxt-link to="/editCustomer">محمد شریفی</nuxt-link>
                        </strong>
                        <br>
                        <code>amirpeace1080@gmail.com</code>
                        <br>
                        باغ فیض روبروی تیراژه
                        <br>
                        اشرفی اصفهانی
                        <br>
                        برزیل
                    </p>
                </div>

                <div class="column">
                    <!-- ستون سمت چپ برای لیست کتاب ها -->
                </div>

            </div>

        </div>

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
      title: 'تغییر سفارشات'
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
