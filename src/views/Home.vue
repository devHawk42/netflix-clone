<template>
  <div class="home">
    <Landing msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Landing from '@/components/Landing.vue';

export default {
  name: 'home',
  components: {
    Landing,
  },
};
</script>
