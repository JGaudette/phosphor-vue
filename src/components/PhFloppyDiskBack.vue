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
    <g v-if="weight === 'bold'"><path d="M40,91.3V208a8,8,0,0,0,8,8H208a8,8,0,0,0,8-8V48a8,8,0,0,0-8-8H91.3a7.9,7.9,0,0,0-5.6,2.3L42.3,85.7A7.9,7.9,0,0,0,40,91.3Z" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="128" cy="148" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><polyline points="104 80 160 80 160 40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><path d="M208,40H91.3a7.9,7.9,0,0,0-5.6,2.3L42.3,85.7A7.9,7.9,0,0,0,40,91.3V208a8,8,0,0,0,8,8H208a8,8,0,0,0,8-8V48A8,8,0,0,0,208,40ZM128,176a28,28,0,1,1,28-28A28,28,0,0,1,128,176Z" opacity="0.2"/><path d="M40,91.3V208a8,8,0,0,0,8,8H208a8,8,0,0,0,8-8V48a8,8,0,0,0-8-8H91.3a7.9,7.9,0,0,0-5.6,2.3L42.3,85.7A7.9,7.9,0,0,0,40,91.3Z" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="128" cy="148" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="96 80 160 80 160 40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M208,32H172a4,4,0,0,0-4,4V80a8,8,0,0,1-8,8H96.3A8.2,8.2,0,0,1,88,80.5,8,8,0,0,1,96,72h56V36a4,4,0,0,0-4-4H91.3A15.9,15.9,0,0,0,80,36.7L36.7,80A15.9,15.9,0,0,0,32,91.3V208a16,16,0,0,0,16,16H208a16,16,0,0,0,16-16V48A16,16,0,0,0,208,32ZM128,176a28,28,0,1,1,28-28A28.1,28.1,0,0,1,128,176Z"/></g>
    <g v-else-if="weight === 'light'"><path d="M40,91.3V208a8,8,0,0,0,8,8H208a8,8,0,0,0,8-8V48a8,8,0,0,0-8-8H91.3a7.9,7.9,0,0,0-5.6,2.3L42.3,85.7A7.9,7.9,0,0,0,40,91.3Z" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="128" cy="148" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><polyline points="96 80 160 80 160 40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><path d="M40,91.3V208a8,8,0,0,0,8,8H208a8,8,0,0,0,8-8V48a8,8,0,0,0-8-8H91.3a7.9,7.9,0,0,0-5.6,2.3L42.3,85.7A7.9,7.9,0,0,0,40,91.3Z" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="128" cy="148" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><polyline points="96 80 160 80 160 40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><path d="M40,91.3V208a8,8,0,0,0,8,8H208a8,8,0,0,0,8-8V48a8,8,0,0,0-8-8H91.3a7.9,7.9,0,0,0-5.6,2.3L42.3,85.7A7.9,7.9,0,0,0,40,91.3Z" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="128" cy="148" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><polyline points="96 80 160 80 160 40" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
