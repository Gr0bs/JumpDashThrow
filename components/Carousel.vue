<template>
  <ul class="flex justify-center">
    <li
      class="mx-4" 
      v-for="(item, i) of list" :key="i">
      <p class="text-center">{{ item.name }}</p>
      <img :src="item.img" alt="">
      <p class="text-center">{{ item.date }}</p>
    </li>
  </ul>
</template>

<script>
export default {
  props: ['list']

}
</script>

<style>

</style>
