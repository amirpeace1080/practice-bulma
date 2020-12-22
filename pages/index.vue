<template>
  <div>
    <!-- <h1 class="title has-text-centered has-text-info">Home Page</h1>
    <br /><br /> -->

    <nav class="navbar has-shadow is-light">
      <div class="navbar-brand">
        <a href="#" class="navbar-item">
          <img src="images/logo.png" alt="">
        </a>
        <div class="navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>


      <div class="navbar-menu">
        <div class="navbar-start">
          <div class="navbar-item">
            <small>item01</small>
          </div>
        </div>

        <div class="navbar-end">
          <div class="navbar-item has-dropdown is-hoverable">
            <div class="navbar-link">
              amirpeace1080
            </div>
            <div class="navbar-dropdown">

              <a href="#" class="navbar-item">
                <div>
                  <span>پروفایل</span>
                  <span class="icon is-small">
                    <i class="fa fa-user-circle"></i>
                  </span>
                  <span></span>
                </div>
              </a>

              <a href="#" class="navbar-item">
                <div>
                  <span>گزارشات</span>
                  <span class="icon is-small">
                    <i class="fa fa-bug"></i>
                  </span>
                  <span></span>
                </div>
              </a>

              <a href="#" class="navbar-item">
                <div>
                  <span>خروج</span>
                  <span class="icon is-small">
                    <i class="fa fa-signout-out-alt"></i>
                  </span>
                  <span></span>
                </div>
              </a>

            </div>
          </div>
        </div>
      </div>
    </nav>

    <section class="section">
      <div class="columns">

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

                <div class="level-item">
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
        </div>



        <div class="column is-4-tablet is-3-desktop is-2-widescreen">
          <nav class="menu">
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
