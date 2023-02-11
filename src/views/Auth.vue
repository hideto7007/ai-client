<template>
    <div class="auth">
        <h1>物体検知評価可視化</h1>
    </div>
  </template>
  
  <script lang="ts">
  import { Options, Vue } from 'vue-class-component';
  import HelloWorld from '@/components/HelloWorld.vue'; 
  
  @Options({
    components: {
      HelloWorld,
    },
  })
  export default class Auth extends Vue {}
  </script>