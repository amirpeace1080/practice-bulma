<template>
  <div>
    <!-- <h1 class="title has-text-centered has-text-info">Home Page</h1>
    <br /><br /> -->

    <div class="container">

      <!-- <div class="columns">
        <div class="column is-half">

          <div class="field">
            <div class="control">
              <input type="text" class="input is-danger is-small is-rounded">
            </div>
          </div>


          <div class="field">
            <div class="control is-loading">
              <input type="text" class="input is-success is-focused">
            </div>
          </div>

          <div class="field">
            <div class="control">
              <input type="text" class="input is-info is-medium is-rounded">
            </div>
          </div>

          <div class="field">
            <div class="control">
              <input type="text" class="input is-warning is-large is-hovered" value="Text" readonly>
            </div>
          </div>

        </div>
      </div> -->

      <div class="columns">
        <div class="column is-half">

          <div class="field">
            <p class="control has-icons-left has-icons-right">
              <input type="email" class="input" placeholder="Email">
            </p>
          </div>

          <div class="field">
            <div class="control">
              <input type="password" class="input" placeholder="Password">
            </div>
          </div>

        </div>
      </div>
      

    </div>

  </div>
</template>

<script>
export default {}
</script>

<style>
.center {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
