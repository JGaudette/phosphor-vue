/* GENERATED FILE */
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 256 256"
    :width="size"
    :height="size"
    :fill="color"
    :transform="mirrored ? 'scale(-1, 1)' : undefined"
    v-bind="$attrs"
  >
    <slot />
    <g v-if="weight === 'bold'"><circle cx="68" cy="188" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="68" cy="68" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="188" cy="140" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><path d="M160,144H130.5a47.8,47.8,0,0,1-36.9-17.3L68,96v64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="68" cy="68" r="28" opacity="0.2"/><circle cx="68" cy="188" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="68" cy="68" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="188" cy="140" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><path d="M160,144H130.5a47.8,47.8,0,0,1-36.9-17.3L68,96v64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M188,104a36.1,36.1,0,0,0-35.8,32H130.5a40,40,0,0,1-30.8-14.4L82.5,100.9A35.9,35.9,0,1,0,60,103.1v49.8a36,36,0,1,0,16,0V118.1l11.5,13.7a55.4,55.4,0,0,0,43,20.2h23.6A36,36,0,1,0,188,104ZM88,188a20,20,0,1,1-20-20A20.1,20.1,0,0,1,88,188Zm100-28a20,20,0,1,1,20-20A20.1,20.1,0,0,1,188,160Z"/></g>
    <g v-else-if="weight === 'light'"><circle cx="68" cy="188" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="68" cy="68" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="188" cy="140" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><path d="M160,144H130.5a47.8,47.8,0,0,1-36.9-17.3L68,96v64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><circle cx="68" cy="188" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="68" cy="68" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="188" cy="140" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><path d="M160,144H130.5a47.8,47.8,0,0,1-36.9-17.3L68,96v64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><circle cx="68" cy="188" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="68" cy="68" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="188" cy="140" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><path d="M160,144H130.5a47.8,47.8,0,0,1-36.9-17.3L68,96v64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
  </svg>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { SetupIconProps, PropValidator, PhosphorIcon } from "@/lib/types";
import useDefaultPropsFromContext from "@/lib/useDefaultPropsFromContext";

const component: PhosphorIcon = defineComponent({
  props: PropValidator,
  setup(props: SetupIconProps) {
    return { ...useDefaultPropsFromContext(props) };
  }
});
export default component;
</script>
