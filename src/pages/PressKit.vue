<template>
  <div id="app">
    <transition name="fade" appear="true">
      <div class="inner-container"> 
        <div class="main">
          <img class="gallery-image" alt="concept-art-one" src="public/images/gallery/concept-art-one.png">
          <img class="gallery-image" alt="concept-art-one" src="public/images/gallery/concept-art-two.png">
          <img class="gallery-image" alt="concept-art-one" src="public/images/gallery/concept-art-three.png">
          <img class="gallery-image" alt="concept-art-one" src="public/images/gallery/concept-art-four.jpg">
        </div>
      </div>
    </transition>
  </div>
</template>

<script>
import Header from '../components/Header.vue';

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>