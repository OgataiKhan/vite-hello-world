<script>
import TitleComponent from '../components/jumbotron/AppTitle.vue';

export default {
  name: 'JumbotronComponent',
  data() {
    return {

    };
  },
  components: {
    TitleComponent,
  },
};

</script>

<template>
  <div class="container">
    <TitleComponent />
    <p>This is a jumbotron. Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate accusamus saepe dolores enim nam, blanditiis asperiores facilis quibusdam dolorem ea ex delectus illum voluptas deserunt! Explicabo repudiandae officia impedit alias!</p>
  </div>
</template>

<style scoped>
  .container {
    background-color: #7f5af0;
    text-align: center;
    padding-top: 100px;
    padding-bottom: 100px;
  }

  .container p {
    max-width: 1000px;
    margin: 0 auto;
    font-weight: 500;
  }
</style>
