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
    <g v-if="weight === 'bold'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="108 100 132 84 132 176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="128" cy="128" r="96" opacity="0.2"/><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-miterlimit="10" stroke-width="16"/><polyline points="108 100 132 84 132 176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M128,24A104,104,0,1,0,232,128,104.2,104.2,0,0,0,128,24Zm12,152a8,8,0,0,1-16,0V98.9l-11.6,7.8a8,8,0,0,1-8.8-13.4l24-16a8.3,8.3,0,0,1,8.2-.4A8,8,0,0,1,140,84Z"/></g>
    <g v-else-if="weight === 'light'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="108 100 132 84 132 176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="108 100 132 84 132 176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-miterlimit="10" stroke-width="16"/><polyline points="108 100 132 84 132 176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
