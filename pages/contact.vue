<template>
  <div class="container">
    <h1 class="text-center display-3 mb-5">Contact Us</h1>
    <div>
      <b-table striped hover :items="items"></b-table>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items:[{'Contact Medium': 'Email', 'Contact Information': 'ITNADigital@gmail.com '}, {'Contact Medium': 'Discord', 'Contact Information': 'ITNA#7616'}, {'Contact Medium': 'Reddit', 'Contact Information': 'u/ITNADigital'}, {'Contact Medium': 'Twitter', 'Contact Information': '@ITNADigital'}]
    }
  }
}
</script>

<style>
</style>