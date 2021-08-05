<template>
  <div class="group">
    <label>{{ rotate }}: {{ perspective }}px;</label>
    <input type="range" min="0" max="999" />
  </div>
</template>

<script>
export default {
  name: "InputItem",
  prop: {
    type: String,
    min: String,
    max: String,
    rotate: String,
  },
};
</script>

