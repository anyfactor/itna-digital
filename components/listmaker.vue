<template>
  <div>
    <div>
      <h2 class='py-4'>
        {{ header }}
      </h2>
      <ul v-for="item in items" :key="item.id" class="h4 text-body">
        <li class="m-3">{{ item }}</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  props: ['header', 'items']
}
</script>

<style>

</style>