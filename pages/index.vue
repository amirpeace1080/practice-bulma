<template>
  <div class="home">
    <!-- <h1 class="title has-text-centered has-text-info">Home Page</h1>
    <br /><br /> -->

    <section class="hero is-primary is-fullheight">
      <div class="hero-body">
        
        <div class="container">
          <div class="columns is-centered">

            <div class="column is-5-tablet is-4-desktop is-3-widescreen">
              <form class="box">

                <div class="field has-text-centered">
                  <img src="images/logo-bis.png" width="167">
                </div>

                <div class="field">
                  <label class="label">ایمیل</label>
                  <div class="control has-icons-right">
                    <input type="email" class="input" placeholder="ایمیل را وارد نمایید" required>
                    <span class="icon is-small is-right">
                      <i class="fa fa-user"></i>
                    </span>
                  </div>
                </div>

                <div class="field">
                  <label class="label">رمز عبور</label>
                  <div class="control has-icons-right">
                    <input type="password" class="input" placeholder="رمز عبور را وارد نمایید" required>
                    <span class="icon is-small is-right">
                      <i class="fa fa-lock"></i>
                    </span>
                  </div>
                </div>

                <div class="field">
                  <label class="checkbox">
                    <input type="checkbox">
                    مرا به خاطر سپار
                  </label>
                </div>

                <div class="field">
                  <button class="button is-success">ورود</button>
                </div>

              </form>
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
      title: 'ورود کاربران'
    }
  }
}
</script>

<style>
.home{
  direction: rtl;
}
</style>
