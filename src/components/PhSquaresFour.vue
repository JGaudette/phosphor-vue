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
    <g v-if="weight === 'bold'"><rect x="48" y="48" width="60" height="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><rect x="148" y="48" width="60" height="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><rect x="48" y="148" width="60" height="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><rect x="148" y="148" width="60" height="60" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><rect x="48" y="48" width="64" height="64" opacity="0.2"/><rect x="144" y="48" width="64" height="64" opacity="0.2"/><rect x="48" y="144" width="64" height="64" opacity="0.2"/><rect x="144" y="144" width="64" height="64" opacity="0.2"/><rect x="144" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><rect x="48" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><rect x="144" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><rect x="48" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><rect x="40" y="40" width="80" height="80" rx="8"/><rect x="136" y="40" width="80" height="80" rx="8"/><rect x="40" y="136" width="80" height="80" rx="8"/><rect x="136" y="136" width="80" height="80" rx="8"/></g>
    <g v-else-if="weight === 'light'"><rect x="48" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><rect x="144" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><rect x="48" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><rect x="144" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><rect x="48" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><rect x="144" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><rect x="48" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><rect x="144" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><rect x="48" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><rect x="144" y="48" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><rect x="48" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><rect x="144" y="144" width="64" height="64" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
