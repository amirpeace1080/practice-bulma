<template>
  <div>
    <!-- <h1 class="title has-text-centered has-text-info">Home Page</h1>
    <br /><br /> -->

    <div class="container">

      <div class="media">

      <!-- media left -->
      <div class="media-left has-background-danger">
        M Left
      </div>

      <!-- media content -->
      <div class="media-content has-background-info">
        M Content

        <div class="media">
          <div class="media-left has-background-success">
            M Left Nested
          </div>

          <div class="media-content has-background-black">
            M Content Nested
          </div>

        </div>

      </div>

      <!-- media-right -->
      <div class="media-right has-background-warning">
        M right
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
