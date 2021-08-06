<template>
  <button class="btn" @click.prevent="handleClick">{{ msg }}</button>
</template>

<script>
export default {
  name: "Button",
  props: {
    msg: String,
    handleClick: Function,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

