<template>
  <div class="home">
    <!--<HelloWorld msg="7"/>-->
    <img src="../assets/loading.gif" alt="7. Basamak Yapım Aşamasında ;)">
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>
