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
    <g v-if="weight === 'bold'"><line x1="204" y1="136" x2="244" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="108" cy="100" r="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><path d="M22.2,200a112,112,0,0,1,171.6,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="108" cy="100" r="60" opacity="0.2"/><line x1="200" y1="136" x2="248" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="108" cy="100" r="60" fill="none" :stroke="color" stroke-miterlimit="10" stroke-width="16"/><path d="M22.2,200a112,112,0,0,1,171.6,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M256,136a8,8,0,0,1-8,8H200a8,8,0,0,1,0-16h48A8,8,0,0,1,256,136ZM144.1,157.6a68,68,0,1,0-72.2,0,118.4,118.4,0,0,0-55.8,37.3,7.8,7.8,0,0,0-1.1,8.5,7.9,7.9,0,0,0,7.2,4.6H193.8a7.9,7.9,0,0,0,7.2-4.6,7.8,7.8,0,0,0-1.1-8.5A118.4,118.4,0,0,0,144.1,157.6Z"/></g>
    <g v-else-if="weight === 'light'"><line x1="200" y1="136" x2="248" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="108" cy="100" r="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><path d="M22.2,200a112,112,0,0,1,171.6,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><line x1="200" y1="136" x2="248" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="108" cy="100" r="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><path d="M22.2,200a112,112,0,0,1,171.6,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><line x1="200" y1="136" x2="248" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="108" cy="100" r="60" fill="none" :stroke="color" stroke-miterlimit="10" stroke-width="16"/><path d="M22.2,200a112,112,0,0,1,171.6,0" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
