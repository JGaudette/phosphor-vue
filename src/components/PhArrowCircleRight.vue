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
    <g v-if="weight === 'bold'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="134.1 161.9 168 128 134.1 94.1" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="88" y1="128" x2="168" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="128" cy="128" r="96" opacity="0.2"/><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-miterlimit="10" stroke-width="16"/><polyline points="134.1 161.9 168 128 134.1 94.1" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="88" y1="128" x2="168" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M128,24A104,104,0,1,0,232,128,104.2,104.2,0,0,0,128,24Zm47.4,107.1a8.7,8.7,0,0,1-1.8,2.6l-33.9,33.9a7.6,7.6,0,0,1-5.6,2.3,7.8,7.8,0,0,1-5.7-2.3,8,8,0,0,1,0-11.3L148.7,136H88a8,8,0,0,1,0-16h60.7L128.4,99.7a8,8,0,0,1,11.3-11.3l33.9,33.9a8.7,8.7,0,0,1,1.8,2.6A8.3,8.3,0,0,1,175.4,131.1Z"/></g>
    <g v-else-if="weight === 'light'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="134.1 161.9 168 128 134.1 94.1" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="88" y1="128" x2="168" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="134.1 161.9 168 128 134.1 94.1" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="88" y1="128" x2="168" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><circle cx="128" cy="128" r="96" fill="none" :stroke="color" stroke-miterlimit="10" stroke-width="16"/><polyline points="134.1 161.9 168 128 134.1 94.1" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="88" y1="128" x2="168" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
