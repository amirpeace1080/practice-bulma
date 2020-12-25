<template>
  <div>
    <section class="section" dir="rtl">
      <div class="columns">
        <!-- start main menu -->
        <MainMenu />
        <!-- end main menu -->

        <!-- start toolbar -->
        <div class="column" dir="">
          <div class="level">
            <div class="level-left">
              <h1 class="subttitle is-5">
                <span class="has-text-grey-light"> خوش آمدید </span
                ><strong> علی حاتمی </strong>
              </h1>
            </div>
            <div class="level-right">
              <div class="select">
                <select>
                  <option>امروز</option>
                  <option>دیروز</option>
                  <option>این هفته</option>
                  <option selected>این ماه</option>
                  <option>امسال</option>
                  <option>همه وقت</option>
                </select>
              </div>
            </div>
          </div>

          <div class="columns is-multiline">
            <div class="column is-12-tablet is-6-desktop is-3-widescreen">
              <div class="notification is-link has-text-right">
                <p class="title is-3">232</p>
                <p class="subtitle is-5">سفارش ها</p>
              </div>
            </div>

            <div class="column is-12-tablet is-6-desktop is-3-widescreen">
              <div class="notification is-info has-text-right">
                <p class="title is-3">7,600,000</p>
                <p class="subtitle is-5">درآمد به تومان</p>
              </div>
            </div>

            <div class="column is-12-tablet is-6-desktop is-3-widescreen">
              <div class="notification is-primary has-text-right">
                <p class="title is-3">1,678</p>
                <p class="subtitle is-5">کتاب ها</p>
              </div>
            </div>

            <div class="column is-12-tablet is-6-desktop is-3-widescreen">
              <div class="notification is-success has-text-right">
                <p class="title is-3">20,756</p>
                <p class="subtitle is-5">بازدیدکنندگان</p>
              </div>
            </div>

            <div class="column is-12-tablet is-6-desktop is-4-fullhd">
                <div class="card">
                    <div class="card-content">
                        <h2 class="title size-4">آخرین سفارش ها</h2>
                        <div class="level">
                            <div class="level-left">
                                <div class="has-text-right">
                                    <p class="title is-5 is-marginless">56000تومان</p>
                                    <span class="tag is-warning">درحال پردازش</span>
                                </div>
                            </div>

                            <div class="level-right">
                                <div>
                                    <p class="title is-5 is-marginless">
                                        <nuxt-link to="/editOrder">TC-12343</nuxt-link>
                                    </p>
                                    <small>
                                        2020/12/28, 19:27:34 توسط <nuxt-link to="/editCustomer">محمد شریفی</nuxt-link>
                                    </small>
                                </div>
                                
                            </div>

                        </div>

                        
                         <div class="level">
                            <div class="level-left">
                                <div class="has-text-right">
                                    <p class="title is-5 is-marginless">34000تومان</p>
                                    <span class="tag is-success">موفقیت آمیز</span>
                                </div>
                            </div>

                            <div class="level-right">
                                <div>
                                    <p class="title is-5 is-marginless">
                                        <nuxt-link to="/editOrder">LM-12343</nuxt-link>
                                    </p>
                                    <small>
                                        2020/12/29, 14:07:34 توسط <nuxt-link to="/editCustomer">امیر دولتی</nuxt-link>
                                    </small>
                                </div>
                                
                            </div>

                        </div>

                        <nuxt-link to="/orders" class="button is-link is-outlined">نمایش همه سفارشات</nuxt-link>

                    </div>
                </div>
            </div>


            <div class="column is-12-tablet is-6-desktop is-4-fullhd">
                <div class="card">
                    <div class="card-content">
                        <h2 class="title size-4">محبوب ترین کتاب ها</h2>
                        
                        <div class="media">
                          <div class="media-left is-marginless">
                            <p class="number">2</p>
                          </div>

                          <div class="media-right">
                            <img src="images/raz.jpg" width="60">
                          </div>

                          <div class="media-content">
                            <p class="title is-5 is-marginless">
                              <nuxt-link to="/editBook">کتاب راز</nuxt-link>
                            </p>
                          </div>

                          <div class="media-left">196 فروش</div>
                        </div>

                        <div class="media">
                          <div class="media-left is-marginless">
                            <p class="number">2</p>
                          </div>

                          <div class="media-right">
                            <img src="images/mellat.jpg" width="60">
                          </div>

                          <div class="media-content">
                            <p class="title is-5 is-marginless">
                              <nuxt-link to="/editBook">ملت عشق</nuxt-link>
                            </p>
                          </div>

                          <div class="media-left">132 فروش</div>
                        </div>

                        <div class="media">
                          <div class="media-left is-marginless">
                            <p class="number">2</p>
                          </div>

                          <div class="media-right">
                            <img src="images/raz.jpg" width="60">
                          </div>

                          <div class="media-content">
                            <p class="title is-5 is-marginless">
                              <nuxt-link to="/editBook">کتاب راز</nuxt-link>
                            </p>
                          </div>

                          <div class="media-left">196 فروش</div>
                        </div>

                        <nuxt-link to="/orders" class="button is-link is-outlined">نمایش همه کتاب ها</nuxt-link>

                    </div>
                </div>
            </div>

            <div class="column is-12-tablet is-6-desktop is-4-fullhd">
              <div class="card">
                  <div class="card-content">
                      <h2 class="title is-4">
                          بهترین مشتریان
                      </h2>

                      <div class="media">
                        <div class="media-left is-marginless">
                          <p class="number">1</p>
                      </div>
                      <div class="media-content">
                        <p class="title is-5 is-spaced is-marginless">
                            <a href="editCustomer">حسین احمدی</a>
                        </p>
                        <p class="subtitle is-6">
                            تهران
                        </p>
                      </div>
                      <div class="media-right">
                      9 سفارش
                      </div>
                    </div>
                  </div>

                  <div class="media">
                      <div class="media-left is-marginless">
                          <p class="number">2</p>
                      </div>
                      <div class="media-content">
                        <p class="title is-5 is-spaced is-marginless">
                            <a href="editCustomer">پدرام درخشنده</a>
                        </p>
                        <p class="subtitle is-6">
                            کرج
                        </p>
                      </div>
                      <div class="media-right">
                      7 سفارش
                      </div>
                    </div>

                  

                  <nuxt-link to="/orders" class="button is-link is-outlined">نمایش همه مشتری ها</nuxt-link>

                </div>
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
  components: {
    MainMenu,
  },
  head() {
    return {
      title: 'داشبورد',
    }
  },
}
</script>

<style>
.home {
  direction: rtl;
}
</style>
