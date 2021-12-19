<template>
  <div class="home">
    <ImageRecognizer msg="Welcome to ImageRecognizer Cloud Project"/>
  </div>
</template>

<script>
import ImageRecognizer from '../components/ImageRecognizer.vue';
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    ImageRecognizer,
  },
};
</script>
