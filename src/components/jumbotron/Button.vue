<script>
export default {
  name: 'ButtonComponent',
  data() {
    return {

    };
  },
};

</script>

<template>
  <button class="btn">Click Me!</button>
</template>

<style scoped>
  .btn {
    background-color: #2cb67d;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 8px;
    transition-duration: 0.4s;
}

.btn:hover {
    background-color: #259264;
}
</style>
