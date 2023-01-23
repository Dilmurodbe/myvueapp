<script>
export default {
  name: 'NavbarPage'
}
import "../assets/main.css"
</script>
<template>

<h1 class="heading" style="color: aqua;">this is navbar</h1>
<div v-for="item in 10">
  <li> {{ item }}</li>
</div>
</template>

<style>


</style>
