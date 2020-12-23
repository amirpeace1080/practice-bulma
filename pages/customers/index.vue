<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">


      <!-- start main menu -->
       <MainMenu />
        <!-- end main menu -->


          <!-- start toolbar -->
         <div class="column" style="direction:rtl">
          <h1 class="title">مشتری ها</h1>
          <nav class="level">
            
            <div class="level-left">

              <div class="level-item">
                <p class="subtitle">
                  تعداد <strong>3</strong>
                </p>
              </div>

                <p class="level-item">
                  <nuxt-link to="/newCustomer" class="button is-success">جدید</nuxt-link>
                </p>

                <div class="level-item is-hidden-tablet-only">
                  <div class="field has-addons">

                    <p class="control">
                      <input type="text" class="input" placeholder="نام ، ایمیل">
                    </p>

                    <p class="control">
                      <button class="button">جستجو</button>
                    </p>

                  </div>
                </div>

            </div>


            <div class="level-right">
              <p class="level-item"><strong>همه</strong></p>
              <p class="level-item"><a>با سفارش</a></p>
              <p class="level-item"><a>بدون سفارش</a></p>
            </div>

          </nav>

        <!-- end toolbar -->


        <!-- table start -->
        <table class="table is-hoverable is-fullwidth">
            <thead>
                <tr>
                    <th class="is-narrow">
                    <input type="checkbox">
                </th>
                <th>نام و نام خانوادگی</th>
                <th>ایمیل</th>
                <th>شهر</th>
                <th>سفارشات</th>
                <th>عملیات</th>
                </tr>
            </thead>
            <tfoot>
                <tr>
                    <th class="is-narrow">
                    <input type="checkbox">
                </th>
                <th>نام و نام خانوادگی</th>
                <th>ایمیل</th>
                <th>شهر</th>
                <th>سفارشات</th>
                <th>عملیات</th>
                </tr>
            </tfoot>
            <tbody>
                <tr>
                    <td><input type="checkbox"></td>
                    <td><nuxt-link to="/editCustomer"><strong>حسین احمدی</strong></nuxt-link></td>
                    <td><code>h_hossein@gmail.com</code></td>
                    <td>اردبیل</td>
                    <td><nuxt-link to="/orderCustomer">2</nuxt-link></td>
                    <td>
                        <div class="buttons">
                            <nuxt-link to="" class="button is-small is-danger">حذف</nuxt-link>
                            <nuxt-link to="/editCustomer" class="button is-small is-warning">ویرایش</nuxt-link>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td><input type="checkbox"></td>
                    <td><nuxt-link to="/editCustomer"><strong>ابراهیم ملکی</strong></nuxt-link></td>
                    <td><code>e@poyan@gmail.com</code></td>
                    <td>تهران</td>
                    <td><nuxt-link to="/orderCustomer">5</nuxt-link></td>
                    <td>
                        <div class="buttons">
                            <nuxt-link to="" class="button is-small is-danger">حذف</nuxt-link>
                            <nuxt-link to="/editCustomer" class="button is-small is-warning">ویرایش</nuxt-link>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td><input type="checkbox"></td>
                    <td><nuxt-link to="/editCustomer"><strong>علی محمدی</strong></nuxt-link></td>
                    <td><code>a_mohammdi@gmail.com</code></td>
                    <td>شیراز</td>
                    <td><nuxt-link to="/orderCustomer">1</nuxt-link></td>
                    <td>
                        <div class="buttons">
                            <nuxt-link to="" class="button is-small is-danger">حذف</nuxt-link>
                            <nuxt-link to="/editCustomer" class="button is-small is-warning">ویرایش</nuxt-link>
                        </div>
                    </td>
                </tr>
            </tbody>
        </table>


        <!-- start paggination -->
        <nav class="pagination" dir="rtl">
          <a class="pagination-previous">قبلی</a>
          <a class="pagination-next">بعدی</a>
          <ul class="pagination-list">
            <li>
              <a class="pagination-link">1</a>
            </li>
            <li>
              <span class="pagination-ellipsis">&hellip;</span>
            </li>
            <li>
              <a class="pagination-link">45</a>
            </li>
            <li>
              <a class="pagination-link is-current">46</a>
            </li>
            <li>
              <a class="pagination-link">47</a>
            </li>
            <li>
              <span class="pagination-ellipsis">&hellip;</span>
            </li>
            <li>
              <a class="pagination-link">86</a>
            </li>
          </ul>
        </nav>


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
      title: 'سیستم مدیریت فروش کتاب'
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
