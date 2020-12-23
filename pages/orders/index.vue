<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">


      <!-- start main menu -->
       <MainMenu />
        <!-- end main menu -->


          <!-- start toolbar -->
         <div class="column" style="direction:rtl">
          <h1 class="title">سفارشات</h1>
          <nav class="level">
            
            <div class="level-left">

              <div class="level-item">
                <p class="subtitle">
                  تعداد <strong>2</strong>
                </p>
              </div>


                <div class="level-item is-hidden-tablet-only">
                  <div class="field has-addons">

                    <p class="control">
                      <input type="text" class="input" placeholder="نام مشتری ، شماره سفارس">
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
                    <th>شماره سفارش</th>
                    <th>نام و نام خانوادگی</th>
                    <th>تاریخ و زمان سفارش</th>
                    <th>تعداد کتاب</th>
                    <th>وضعیت</th>
                    <th>قیمت کل(تومان)</th>
                </tr>
            </thead>
            <tfoot>
                <tr>
                    <th>شماره سفارش</th>
                    <th>نام و نام خانوادگی</th>
                    <th>تاریخ و زمان سفارش</th>
                    <th>تعداد کتاب</th>
                    <th>وضعیت</th>
                    <th>قیمت کل(تومان)</th>
                </tr>
            </tfoot>
            <tbody>
                <tr>
                    <td><nuxt-link to="/editOrder"><strong>RS-43312</strong></nuxt-link></td>
                    <td><nuxt-link to="/editCustomer"><strong>محمد شریفی</strong></nuxt-link></td>
                    <td>2020/12/21 17:44</td>
                    <td>2</td>
                    <td>
                        <span class="tag is-warning">در حال پردازش</span>
                    </td>
                    <td>
                        56000
                    </td>
                </tr>
                
                <tr>
                    <td><nuxt-link to="/editOrder"><strong>MG-98126</strong></nuxt-link></td>
                    <td><nuxt-link to="/editCustomer"><strong>سعید زندی</strong></nuxt-link></td>
                    <td>2020/12/17 13:24</td>
                    <td>8</td>
                    <td>
                        <span class="tag is-success">موفقیت آمیز</span>
                    </td>
                    <td>
                        72000
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
      title: 'سفارشات'
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
