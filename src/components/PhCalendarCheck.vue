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
    <g v-if="weight === 'bold'"><rect x="40" y="40" width="176" height="176" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="176" y1="20" x2="176" y2="40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="80" y1="20" x2="80" y2="40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="40" y1="88" x2="216" y2="88" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="164 128 117.3 172 92 148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><path d="M40,88H216V48a8,8,0,0,0-8-8H48a8,8,0,0,0-8,8Z" opacity="0.2"/><rect x="40" y="40" width="176" height="176" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="176" y1="24" x2="176" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="80" y1="24" x2="80" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="40" y1="88" x2="216" y2="88" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="164 128 117.3 172 92 148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M208,32H184V24a8,8,0,0,0-16,0v8H88V24a8,8,0,0,0-16,0v8H48A16,16,0,0,0,32,48V208a16,16,0,0,0,16,16H208a16,16,0,0,0,16-16V48A16,16,0,0,0,208,32ZM169.5,133.8l-46.7,44a7.7,7.7,0,0,1-5.5,2.2,7.9,7.9,0,0,1-5.5-2.2l-25.3-24a8,8,0,1,1,11-11.6L117.3,161l41.2-38.8a7.9,7.9,0,0,1,11.3.3A8,8,0,0,1,169.5,133.8ZM208,80H48V48H72v8a8,8,0,0,0,16,0V48h80v8a8,8,0,0,0,16,0V48h24Z"/></g>
    <g v-else-if="weight === 'light'"><rect x="40" y="40" width="176" height="176" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="176" y1="24" x2="176" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="80" y1="24" x2="80" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="40" y1="88" x2="216" y2="88" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="164 128 117.3 172 92 148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><rect x="40" y="40" width="176" height="176" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="176" y1="24" x2="176" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="80" y1="24" x2="80" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="40" y1="88" x2="216" y2="88" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="164 128 117.3 172 92 148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><rect x="40" y="40" width="176" height="176" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="176" y1="24" x2="176" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="80" y1="24" x2="80" y2="56" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="40" y1="88" x2="216" y2="88" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="164 128 117.3 172 92 148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
