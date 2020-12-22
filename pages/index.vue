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
