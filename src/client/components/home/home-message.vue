<script setup lang="ts">
  // 👇 Not working ❌
  // import { BaseHeading, type BaseHeadingProps } from '../base';

  import { BaseHeading } from '../base';

  // 👇 Not working ❌
  // import type { BaseHeadingProps } from '../base';

  // 👇 Working ✅
  import type { BaseHeadingProps } from './types';

  export type HomeMessageProps = BaseHeadingProps;
  const props = defineProps<HomeMessageProps>();
</script>
<template>
  <BaseHeading :text="props.text" />
</template>
