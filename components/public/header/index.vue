<template>
  <div class="my-header">
    <topbar></topbar>
    <!-- <searchbar></searchbar> -->
  </div>
</template>

<script>
import topbar from './topbar'
import searchbar from './searchbar'
export default {
  components: {
    topbar,
    searchbar
  }
}
</script>
