<template>
  <navbar_1 />
   <navbar_2 />
   <slider/>
   <welcome/>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import navbar_1 from '../components/Navbar_1.vue';
import navbar_2 from '../components/Navbar_2.vue';
import slider from '../components/Slider.vue';
import welcome from '../components/Welcome.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    navbar_1,navbar_2,slider,welcome
  },
});
</script>
