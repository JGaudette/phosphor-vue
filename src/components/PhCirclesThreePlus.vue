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
    <g v-if="weight === 'bold'"><circle cx="74" cy="74" r="34" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="182" cy="74" r="34" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="74" cy="182" r="34" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="182" y1="156" x2="182" y2="208" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="208" y1="182" x2="156" y2="182" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="76" cy="76" r="36" opacity="0.2"/><circle cx="180" cy="76" r="36" opacity="0.2"/><circle cx="76" cy="180" r="36" opacity="0.2"/><circle cx="76" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="180" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="76" cy="180" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="180" y1="152" x2="180" y2="208" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="208" y1="180" x2="152" y2="180" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><circle cx="76" cy="76" r="44"/><circle cx="180" cy="76" r="44"/><circle cx="76" cy="180" r="44"/><path d="M208,172H188V152a8,8,0,0,0-16,0v20H152a8,8,0,0,0,0,16h20v20a8,8,0,0,0,16,0V188h20a8,8,0,0,0,0-16Z"/></g>
    <g v-else-if="weight === 'light'"><circle cx="76" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="180" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="76" cy="180" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="180" y1="152" x2="180" y2="208" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="208" y1="180" x2="152" y2="180" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><circle cx="76" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="180" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="76" cy="180" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="180" y1="152" x2="180" y2="208" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="208" y1="180" x2="152" y2="180" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><circle cx="76" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="180" cy="76" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="76" cy="180" r="36" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="180" y1="152" x2="180" y2="208" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="208" y1="180" x2="152" y2="180" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
