<template>
  <div class="container">
    <h1 class="title has-text-centered has-text-info">Home Page</h1>
    <br /><br />

    <section class="section">
      <div class="container">

        <div class="columns">
          <div class="column">
            <p class="notification is-info">First Column</p>

            <div class="columns is-mobile">
              <div class="column">
                <p class="notification is-info">First Nested column</p>
              </div>

              <div class="column">
                <p class="notification is-info">Second nested Column</p>
              </div>
            </div>
          </div>

          <div class="column">
            <p class="notification is-danger">Second Column</p>

            <div class="columns is-gapless">
              <div class="column is-half">
                <p class="notification is-danger">50%</p>
              </div>

              <div class="column">
              <p class="notification is-danger">Auto</p>
            </div>

            <div class="column">
              <p class="notification is-danger">Auto</p>
            </div>
            </div>

            
          </div>
        </div>

      </div>
    </section>

  </div>
</template>

<script>
export default {}
</script>

<style></style>
