<template>
  <div>
    <b-button v-b-toggle.sidebar-right>Toggle Sidebar</b-button>
    <b-sidebar id="sidebar-1" title="Sidebar" shadow="">
      <div class="px-3 py-2">
        <p>
          testing.testing
        </p>
        <b-img src="app/assets/images/mug.jpg" snowpeak mug></b-img>
      </div>
    </b-sidebar>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!",
      status: "not_accepted"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
