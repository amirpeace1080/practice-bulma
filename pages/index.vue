<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">


      <!-- start main menu -->
       <MainMenu />
        <!-- end main menu -->


          <!-- start toolbar -->
         <div class="column" style="direction:rtl">
          <h1 class="title">کتاب ها</h1>
          <nav class="level">
            
            <div class="level-left">

              <div class="level-item">
                <p class="subtitle">
                  تعداد <strong>6</strong>
                </p>
              </div>

                <p class="level-item">
                  <nuxt-link to="/newBook" class="button is-success">جدید</nuxt-link>
                </p>

                <div class="level-item is-hidden-tablet-only">
                  <div class="field has-addons">

                    <p class="control">
                      <input type="text" class="input" placeholder="نام کتاب ، ISBN">
                    </p>

                    <p class="control">
                      <button class="button">جستجو</button>
                    </p>

                  </div>
                </div>

            </div>


            <div class="level-right">
              <div class="level-item">
                سفارشات براساس

                <div class="level-item">
                  <div class="select">
                    <select>
                      <option>تاریخ انتشار</option>
                      <option>قیمت</option>
                      <option>تعداد صفحه</option>
                    </select>
                  </div>
                </div>
              </div>
            </div>

          </nav>

        <!-- end toolbar -->


        <div class="columns is-multiline" dir="ltr">

          <div class="column is-12-tablet is-6-desktop is-4-widescreen">
            
            <article class="box">
              <div class="media">
                <aside class="media-right">
                  <img src="images/mardi.jpg" width="80">
                </aside>

                <div class="media-content" dir="rtl">
                  <p class="title">
                    <a href="#">
                      مردی به نام اوه
                    </a>
                  </p>
                  <p class="subtitle is-marginless has-text-success">
                    32.000 تومان
                  </p>
                  <div class="content">
                    51 صفحه
                    <br>
                    IBSN: 444-900-7381-213
                    <br>
                    <a href="#">ویرایش</a>
                    <span> . </span>
                    <a href="#">حذف</a>
                  </div>
                </div>

              </div>
            </article>

          </div>

          <div class="column is-12-tablet is-6-desktop is-4-widescreen">
            
            <article class="box">
              <div class="media">
                <aside class="media-right">
                  <img src="images/raz.jpg" width="80">
                </aside>

                <div class="media-content" dir="rtl">
                  <p class="title">
                    <a href="#">
                      راز
                    </a>
                  </p>
                  <p class="subtitle is-marginless has-text-success">
                    72.000 تومان
                  </p>
                  <div class="content">
                    215 صفحه
                    <br>
                    IBSN: 444-900-7381-213
                    <br>
                    <a href="#">ویرایش</a>
                    <span> . </span>
                    <a href="#">حذف</a>
                  </div>
                </div>

              </div>
            </article>
          </div>


          <div class="column is-12-tablet is-6-desktop is-4-widescreen">
            
            <article class="box">
              <div class="media">
                <aside class="media-right">
                  <img src="images/raz.jpg" width="80">
                </aside>

                <div class="media-content" dir="rtl">
                  <p class="title">
                    <a href="#">
                      راز
                    </a>
                  </p>
                  <p class="subtitle is-marginless has-text-success">
                    42.000 تومان
                  </p>
                  <div class="content">
                    215 صفحه
                    <br>
                    IBSN: 444-900-7381-213
                    <br>
                    <a href="#">ویرایش</a>
                    <span> . </span>
                    <a href="#">حذف</a>
                  </div>
                </div>

              </div>
            </article>
          </div>


          <div class="column is-12-tablet is-6-desktop is-4-widescreen">
            
            <article class="box">
              <div class="media">
                <aside class="media-right">
                  <img src="images/raz.jpg" width="80">
                </aside>

                <div class="media-content" dir="rtl">
                  <p class="title">
                    <a href="#">
                      راز
                    </a>
                  </p>
                  <p class="subtitle is-marginless has-text-success">
                    42.000 تومان
                  </p>
                  <div class="content">
                    215 صفحه
                    <br>
                    IBSN: 444-900-7381-213
                    <br>
                    <a href="#">ویرایش</a>
                    <span> . </span>
                    <a href="#">حذف</a>
                  </div>
                </div>

              </div>
            </article>
          </div>


          <div class="column is-12-tablet is-6-desktop is-4-widescreen">
            
            <article class="box">
              <div class="media">
                <aside class="media-right">
                  <img src="images/raz.jpg" width="80">
                </aside>

                <div class="media-content" dir="rtl">
                  <p class="title">
                    <a href="#">
                      راز
                    </a>
                  </p>
                  <p class="subtitle is-marginless has-text-success">
                    42.000 تومان
                  </p>
                  <div class="content">
                    215 صفحه
                    <br>
                    IBSN: 444-900-7381-213
                    <br>
                    <a href="#">ویرایش</a>
                    <span> . </span>
                    <a href="#">حذف</a>
                  </div>
                </div>

              </div>
            </article>
          </div>



          <div class="column is-12-tablet is-6-desktop is-4-widescreen">
            
            <article class="box">
              <div class="media">
                <aside class="media-right">
                  <img src="images/raz.jpg" width="80">
                </aside>

                <div class="media-content" dir="rtl">
                  <p class="title">
                    <a href="#">
                      راز
                    </a>
                  </p>
                  <p class="subtitle is-marginless has-text-success">
                    42.000 تومان
                  </p>
                  <div class="content">
                    215 صفحه
                    <br>
                    IBSN: 444-900-7381-213
                    <br>
                    <a href="#">ویرایش</a>
                    <span> . </span>
                    <a href="#">حذف</a>
                  </div>
                </div>

              </div>
            </article>
          </div>




        </div>

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
