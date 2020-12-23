<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">
        <!-- start main menu -->
        <MainMenu />
        <!-- end main menu -->

        <!-- start breadcrumb -->
        <nav class="breadcrumb">
          <ul>
            <li>
              <nuxt-link to="/customers">مشتریها</nuxt-link>
            </li>
            <li class="is-active">
              <nuxt-link to="/newCustomer">جدید</nuxt-link>
            </li>
          </ul>
        </nav>

        <!-- start form -->
        <form>
          <div class="field">
            <label class="label">نام ونام خانوادگی</label>
            <div class="control">
              <input
                type="text"
                class="input is-large"
                placeholder="محمد شریفی"
                required
              />
            </div>
          </div>

          <div class="field">
            <label class="label">ایمیل</label>
            <div class="control has-icons-left">
              <input
                type="email"
                class="input"
                placeholder="مثال amirpeace1080@gmail.com"
                required
              />
              <span class="icon is-small is-left">
                <i class="fa fa-envelope"></i>
              </span>
            </div>
          </div>

          <div class="field">
            <label class="label">آدرس</label>
            <div class="contro">
              <input
                type="text"
                class="input"
                placeholder="نام خیابان و پلاک"
                required
              />
            </div>
          </div>

          <div class="field">
            <div class="contro">
              <input
                type="text"
                class="input"
                placeholder="آدرس دوم (اختیاری)"
                required
              />
            </div>
          </div>

          <div class="columns is-multiline">
            <div class="column is-6-tablet is-4-desktop">
              <label class="label">کد پستی</label>
              <div class="control">
                <input
                  type="number"
                  class="input"
                  placeholder="123-45678-9"
                  required
                />
              </div>
            </div>

            <div class="column is-6-tablet is-4-desktop">
              <label class="label">شهر</label>
              <div class="control">
                <input
                  type="number"
                  class="input"
                  placeholder="تهران"
                  required
                />
              </div>
            </div>

            <div class="column is-6-tablet is-4-desktop">
              <label class="label">کشور</label>
              <div class="control">
                <div class="select">
                  <select>
                    <option>-- انتخاب کشور --</option>
                    <option>برزیل</option>
                    <option>آرژانتین</option>
                    <option>پرتغال</option>
                  </select>
                </div>
              </div>
            </div>
          </div>

          <div class="field">
            <div class="buttons">
              <button class="button is-medium is-success">ایجاد مشتری</button>
              <button class="button is-medium is-light">لغو</button>
            </div>
          </div>
        </form>
      </div>
    </section>
  </div>
</template>

<script>
import MainMenu from '@/components/MainMenu.vue'

export default {
  components: {
    MainMenu,
  },
  head() {
    return {
      title: 'مشتری جدید',
    }
  },
}
</script>

<style>
.home {
  direction: rtl;
}
</style>
