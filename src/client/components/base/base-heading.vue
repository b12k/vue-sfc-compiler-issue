<script lang="ts" setup>
  export type BaseHeadingProps = {
    text: string;
  };

  const props = defineProps<BaseHeadingProps>();
</script>
<template>
  <h1>{{ props.text }}</h1>
</template>
