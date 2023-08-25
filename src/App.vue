<template>

<HeroVue/>
<InfoVue/>
<GallerieVue/>
<ContactVue/>
<FaqVue/>
<FooterVue/>

</template>

<script>

import HeroVue from "./components/HeroVue.vue";
import InfoVue from "./components/InfoVue.vue";
import GallerieVue from "./components/GallerieVue.vue";
import ContactVue from "./components/ContactVue.vue";
import FaqVue from "./components/FaqVue.vue";
import FooterVue from "./components/FooterVue.vue";

export default {
  components: {
    HeroVue,
    InfoVue,
    GallerieVue,
    ContactVue,
    FaqVue,
    FooterVue,
  },
  setup() {
    // ...
  }
}

</script>

<style>

body {
  margin: 0;
  padding: 0;
}

</style>