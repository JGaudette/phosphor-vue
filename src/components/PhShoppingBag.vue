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
    <g v-if="weight === 'bold'"><rect x="32" y="48" width="192" height="160" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><path d="M168,88a40,40,0,0,1-80,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><rect x="32" y="48" width="192" height="160" rx="8" opacity="0.2"/><rect x="32" y="48" width="192" height="160" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><path d="M168,88a40,40,0,0,1-80,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M216,40H40A16,16,0,0,0,24,56V200a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V56A16,16,0,0,0,216,40Zm-88,96A48,48,0,0,1,80,88a8,8,0,0,1,16,0,32,32,0,0,0,64,0,8,8,0,0,1,16,0A48,48,0,0,1,128,136Z"/></g>
    <g v-else-if="weight === 'light'"><rect x="32" y="48" width="192" height="160" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><path d="M168,88a40,40,0,0,1-80,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><rect x="32" y="48" width="192" height="160" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><path d="M168,88a40,40,0,0,1-80,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><rect x="32" y="48" width="192" height="160" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><path d="M168,88a40,40,0,0,1-80,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
