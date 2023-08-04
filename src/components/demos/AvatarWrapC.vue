<template>
    <div class="demo-type">
      <PAvatar :size="60" src="https://empty" @error="errorHandler">
        <img
          src="https://cube.elemecdn.com/e/fd/0fc7d20532fdaf769a25683617711png.png"
        />
      </PAvatar>
    </div>
  </template>
  
  <script lang="ts" setup>
  import PAvatar from '../elements/PAvatar.vue';
  const errorHandler = () => true
  </script>