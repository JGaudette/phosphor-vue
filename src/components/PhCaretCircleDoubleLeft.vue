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
    <g v-if="weight === 'bold'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="168 160 136 128 168 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="112 160 80 128 112 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="128" cy="128" r="96" opacity="0.2"/><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="168 160 136 128 168 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="112 160 80 128 112 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M201.5,54.5a104,104,0,1,0,0,147A103.9,103.9,0,0,0,201.5,54.5Zm-83.8,99.8a8.1,8.1,0,0,1,0,11.4,8.2,8.2,0,0,1-11.4,0l-32-32a8.1,8.1,0,0,1,0-11.4l32-32a8.1,8.1,0,0,1,11.4,11.4L91.3,128Zm56,0a8.1,8.1,0,0,1,0,11.4,8.2,8.2,0,0,1-11.4,0l-32-32a8.1,8.1,0,0,1,0-11.4l32-32a8.1,8.1,0,0,1,11.4,11.4L147.3,128Z"/></g>
    <g v-else-if="weight === 'light'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="168 160 136 128 168 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="112 160 80 128 112 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="168 160 136 128 168 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="112 160 80 128 112 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="168 160 136 128 168 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="112 160 80 128 112 96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
