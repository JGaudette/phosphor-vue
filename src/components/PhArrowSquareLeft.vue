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
    <g v-if="weight === 'bold'"><rect x="40" y="40" width="176" height="176" rx="8" transform="translate(256 0) rotate(90)" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="121.9 94.1 88 128 121.9 161.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="168" y1="128" x2="88" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><rect x="40" y="40" width="176" height="176" rx="8" transform="translate(256 0) rotate(90)" opacity="0.2"/><rect x="40" y="40" width="176" height="176" rx="8" transform="translate(256 0) rotate(90)" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="121.9 94.1 88 128 121.9 161.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="168" y1="128" x2="88" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M224,208V48a16,16,0,0,0-16-16H48A16,16,0,0,0,32,48V208a16,16,0,0,0,16,16H208A16,16,0,0,0,224,208ZM116.3,167.6,82.4,133.7a8,8,0,0,1-1.8-2.7,7.7,7.7,0,0,1-.6-3,8.5,8.5,0,0,1,.6-3.1,8.7,8.7,0,0,1,1.8-2.6l33.9-33.9a8,8,0,0,1,11.3,11.3L107.3,120H168a8,8,0,0,1,0,16H107.3l20.3,20.3a8,8,0,0,1-11.3,11.3Z"/></g>
    <g v-else-if="weight === 'light'"><rect x="40" y="40" width="176" height="176" rx="8" transform="translate(256 0) rotate(90)" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="121.9 94.1 88 128 121.9 161.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="168" y1="128" x2="88" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><rect x="40" y="40" width="176" height="176" rx="8" transform="translate(256 0) rotate(90)" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="121.9 94.1 88 128 121.9 161.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="168" y1="128" x2="88" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><rect x="40" y="40" width="176" height="176" rx="8" transform="translate(256 0) rotate(90)" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="121.9 94.1 88 128 121.9 161.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="168" y1="128" x2="88" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
