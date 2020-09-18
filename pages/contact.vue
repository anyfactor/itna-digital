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
      items:[{'Contact Medium': 'Email', 'Contact Information': 'anyfactor@gmail.com '}, {'Contact Medium': 'Discord', 'Contact Information': 'anyfactor#8591'}, {'Contact Medium': 'Reddit', 'Contact Information': '@anyfactor'}, {'Contact Medium': 'Twitter', 'Contact Information': 'anyfactor@gmail.com'}, {'Contact Medium': 'Skype', 'Contact Information': 'anyfactor@gmail.com'}]
    }
  }
}
</script>

<style>
</style>