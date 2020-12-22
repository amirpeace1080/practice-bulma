<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">


      <!-- start main menu -->
        <div class="column is-4-tablet is-3-desktop is-2-widescreen">
          <nav class="menu" dir="rtl">
            <p class="menu-label">
              منوی اصلی
            </p>
            <ul class="menu-list">

              <li>
                <nuxt-link to="/dashboard">
                  <span class="icon">
                    <i class="fa fa-digital-tachograph"></i>
                  </span>
                  داشبورد
                </nuxt-link>
              </li>

              <li>
                <a href="/book" class="is-active">
                  <span class="icon">
                    <i class="fa fa-book"></i>
                  </span>
                  کتاب ها
                </a>
              </li>

              <li>
                <nuxt-link to="/customers">
                  <span class="icon">
                    <i class="fa fa-address-book"></i>
                  </span>
                  مشتری ها
                </nuxt-link>
              </li>

              <li>
                <nuxt-link to="/orders">
                  <span class="icon">
                    <i class="fa fa-file"></i>
                  </span>
                  سفارشات
                </nuxt-link>
              </li>

            </ul>
          </nav>
        </div>

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
                  <a href="#" class="button is-success">جدید</a>
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


        </div>


      </div>
    </section>
    
  </div>
</template>

<script>
export default {
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
