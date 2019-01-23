<template>
<b-navbar toggleable="md" type="dark" variant="danger">

  <b-container>

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand href="#">Redditaisai</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">
      <!-- TODO(james7132): Add search back in -->
      <!-- TODO(james7132): Add localiation back in -->
    </b-navbar-nav>

  </b-collapse>
  </b-container>
</b-navbar>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style>
.navbar {
  -webkit-box-shadow: 0 8px 6px -6px #999;
  -moz-box-shadow: 0 8px 6px -6px #999;
  box-shadow: 0 8px 6px -6px #999;
}
</style>
