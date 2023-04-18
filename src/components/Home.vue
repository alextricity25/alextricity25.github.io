<template>
  <div id="home" class="centerStage">
    <div
        class="bg-image text-center"
        style="
        background-image: url('https://www.dropbox.com/s/wmqtbjo1mow1umf/IMG_9517.JPG?raw=true');
        height: 100vh;">
      <NamePlate />
      <SocialMediaReel />
    </div>
  </div>
</template>


<script>
import NamePlate from './NamePlate.vue';
import SocialMediaReel from './SocialMediaReel.vue';

export default {
  components: {
    NamePlate,
    SocialMediaReel
  },
  name: 'home',
  data: function () {
    return {
    }
  },
  created () { },
  methods: {
    async setup () {
    },
  }
}
</script>
