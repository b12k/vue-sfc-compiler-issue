<script lang="ts" setup>
  import { HomeMessage, type HomeMessageProps } from '../components';

  const messageProps: HomeMessageProps = {
    text: 'Banana',
  };
</script>

<template>
  <main class="page-home">
    <HomeMessage :text="messageProps.text" />
  </main>
</template>
