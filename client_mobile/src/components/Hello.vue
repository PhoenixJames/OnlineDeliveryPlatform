<template>
  <div>
    <div class="my-2">
      <v-btn small color="primary">Primary</v-btn>
    </div>
    <div class="my-2">
      <v-btn small color="error">Error</v-btn>
    </div>
    <div class="my-2">
      <v-btn small disabled>Disabled</v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js PWA',
    };
  },
};
</script>
