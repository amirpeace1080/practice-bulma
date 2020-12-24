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
                    <p class="heading">
                      <strong>کتاب ها</strong>
                    </p>
                    <table class="table is-bordered is-fullwidht">
                      <thead>
                        <tr>
                          <td class="is-narrow">جلد کتاب</td>
                          <td>عنوان</td>
                          <td class="has-text-right is-narrow">قیمت</td>
                          <td class="has-text-right is-narrow">تعداد سفارش</td>
                          <td class="has-text-right is-narrow">قیمت کل</td>
                        </tr>
                      </thead>
                      <tfoot>
                        <tr>
                          <td colspan="5" class="has-text-right">58.000 تومان</td>
                        </tr>
                      </tfoot>

                      <tbody>
                        <tr>
                          <td>
                            <img src="images/raz.jpg" width="40">
                          </td>
                          <td>
                            <nuxt-link to="/editBook"><strong>راز</strong></nuxt-link>
                          </td>
                          <td class="has-text-right">21.000</td>
                          <td>
                            <input type="number" class="input is-small" value="2" maxlength="2" max="2">
                          </td>
                          <td class="has-text-right">42.000</td>
                        </tr>


                        <tr>
                          <td>
                            <img src="images/mellat.jpg" width="40">
                          </td>
                          <td>
                            <nuxt-link to="/editBook"><strong>ملت عشق</strong></nuxt-link>
                          </td>
                          <td class="has-text-right">8.000</td>
                          <td>
                            <input type="number" class="input is-small" value="2" maxlength="2" max="2">
                          </td>
                          <td class="has-text-right">16.000</td>
                        </tr>

                        <tr>
                          <td colspan="5">
                            <div class="field is-grouped is-grouped-left">
                              <div class="control">
                                <div class="select is-small">
                                  <select>
                                    <option>ملت عشق</option>
                                    <option>راز</option>
                                    <option>اسکندر</option>
                                    <option>شب های روشن</option>
                                    <option>کتاب کیمیاگر</option>
                                    <option>مردی به نام اوه</option>
                                  </select>
                                </div>
                              </div>

                              <div class="control">
                                <input type="number" class="input is-small" value="1" placeholder="تعداد" maxlength="2" max="9">
                              </div>

                              <div class="control">
                                <nuxt-link to="" class="button is-small is-link">اضافه کردن کتاب</nuxt-link>
                              </div>
                            </div>
                          </td>
                        </tr>
                      </tbody>

                    </table>
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
