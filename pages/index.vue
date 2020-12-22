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

        <div class="column">

        </div>


        <div class="column is-4-tablet is-3-desktop is-2-widescreen">
          <nav class="menu">
            <p class="menu-label">
              منوی اصلی
            </p>
            <ul class="menu-list">

              <li>
                <a href="#">
                  <span class="icon">
                    <i class="fa fa-digital-tachograph"></i>
                  </span>
                  داشبورد
                </a>
              </li>

              <li>
                <a href="#">
                  <span class="icon">
                    <i class="fa fa-book"></i>
                  </span>
                  کتاب ها
                </a>
              </li>

              <li>
                <a href="#">
                  <span class="icon">
                    <i class="fa fa-address-book"></i>
                  </span>
                  مشتری ها
                </a>
              </li>

              <li>
                <a href="#">
                  <span class="icon">
                    <i class="fa fa-file"></i>
                  </span>
                  سفارشات
                </a>
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
