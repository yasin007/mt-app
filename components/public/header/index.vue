<template>
  <div class="m-header">
    <el-row>
      <el-col>
        <top-bar></top-bar>
      </el-col>
      <el-col>
        <search-bar></search-bar>
      </el-col>
    </el-row>
  </div>

</template>

<script>
  import topBar from './topbar.vue'
  import searchBar from './saerchbar.vue'

  export default {
    components: {
      topBar,
      searchBar
    }
  }
</script>

<style lang="scss">

</style>
