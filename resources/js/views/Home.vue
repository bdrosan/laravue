<template>
  <div>Home</div>
  <button @click="showAlert">Test SweetAlert</button>
</template>

<script>
export default {
  methods: {
    showAlert() {
      // Use sweetalert2
      this.$swal("Hello Vue world!!!");
    },
  },
};
</script>

<style>
</style>