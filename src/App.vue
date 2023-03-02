<template>
  <div class="app">
    <Guides />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Guides from './components/Guides.vue';

export default defineComponent({
  components: {
    Guides
  },
});
</script>

<style>
/* 
black marmore #040501 || #b69d59 || #848484
white marmore #f1edea || #e8be5b || #bca990
*/

*{
  margin: 0;
  padding: 0;
  border: none;
}

.app {
  width: 100vw;
  height: 100vh;
  background-image: url("@/assets/whitemarmore.jpg");
  background-size: 100% 100%;
}

</style>
