<template>
  <button class="btn btn-primary">
      <i :class="['fa', 'fa-2x', icon]"></i>
  </button>
</template>

<script>
export default {
  props:{
    icon: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
button{
    border-radius: 80%;
    bottom: 20px;
    height: 80px;
    position: fixed;
    right: 20px;
    width: 80px;
}
</style>