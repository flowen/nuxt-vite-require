<template>
  <div>
    test

    <img :src="image" alt="" />
  </div>
</template>

<script>
export default {
  name: 'Test',
  props: {
    image: {
      type: String,
      default: null,
      required: true,
    },
  },
}
</script>

<style></style>
