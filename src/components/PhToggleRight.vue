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
    <g v-if="weight === 'bold'"><rect x="16" y="64" width="224" height="128" rx="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="176" cy="128" r="24" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="176" cy="128" r="32" opacity="0.2"/><rect x="16" y="64" width="224" height="128" rx="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="176" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M176,56H80a72,72,0,0,0,0,144h96a72,72,0,0,0,0-144Zm0,112a40,40,0,1,1,40-40A40,40,0,0,1,176,168Z"/></g>
    <g v-else-if="weight === 'light'"><rect x="16" y="64" width="224" height="128" rx="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="176" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><rect x="16" y="64" width="224" height="128" rx="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="176" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><rect x="16" y="64" width="224" height="128" rx="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="176" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
