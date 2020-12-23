<template>
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
                <nuxt-link to="/" exact>
                  <span class="icon">
                    <i class="fa fa-book"></i>
                  </span>
                  کتاب ها
                </nuxt-link>
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

</template>



<style>
  .nuxt-link-active{
    background: #3273DC;
  }
</style>