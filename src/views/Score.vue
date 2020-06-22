<template>
  <div class="about">
    <p>{{ count }}</p>
    <p>現在のスコア</p>
  </div>
</template>

<script>
export default {
  computed:{
    count(){return this.$store.getters.count}
  }
}
</script>