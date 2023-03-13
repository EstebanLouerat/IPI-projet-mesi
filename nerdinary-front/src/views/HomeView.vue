<template>
  <v-app>
    <NavBar />
    <v-lazy :min-height="1000" />
    
    <FooterView />
  </v-app>
  
</template>

<script>
import { defineComponent } from 'vue';

// Components
import NavBar from '@/components/NavBar.vue';
import FooterView from '@/components/FooterView.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    NavBar,
    FooterView
},
});
</script>

<style scoped>

</style>