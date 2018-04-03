<template>
  <div>
    <p class="card">
      {{text}}
    </p>
    <p>
    	{{name}}
    </p>
  </div>
</template>

<script>
export default {
  props: ['text',"name"]
}
</script>

<style>
.card {
  padding: 10px;
}
</style>
