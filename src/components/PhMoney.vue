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
    <g v-if="weight === 'bold'"><rect x="16" y="64" width="224" height="128" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="128" cy="128" r="28" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="168" y1="64" x2="240" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="168" y1="192" x2="240" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="88" y1="64" x2="16" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="88" y1="192" x2="16" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><circle cx="128" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="128" cy="128" r="32" opacity="0.2"/><path d="M232,64H176l64,56V72A8,8,0,0,0,232,64Z" opacity="0.2"/><path d="M232,192a8,8,0,0,0,8-8V136l-64,56Z" opacity="0.2"/><path d="M16,72v48L80,64H24A8,8,0,0,0,16,72Z" opacity="0.2"/><path d="M16,184a8,8,0,0,0,8,8H80L16,136Z" opacity="0.2"/><rect x="16" y="64" width="224" height="128" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="176" y1="64" x2="240" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="176" y1="192" x2="240" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="80" y1="64" x2="16" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="80" y1="192" x2="16" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M232,56H24A16,16,0,0,0,8,72V184a16,16,0,0,0,16,16H232a16,16,0,0,0,16-16V72A16,16,0,0,0,232,56ZM75,184,24,140.3V115.7L75,72H181l51,43.7v24.6L181,184Zm93-56a40,40,0,1,1-40-40A40,40,0,0,1,168,128Z"/></g>
    <g v-else-if="weight === 'light'"><rect x="16" y="64" width="224" height="128" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><circle cx="128" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="176" y1="64" x2="240" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="176" y1="192" x2="240" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="80" y1="64" x2="16" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="80" y1="192" x2="16" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><rect x="16" y="64" width="224" height="128" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><circle cx="128" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="176" y1="64" x2="240" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="176" y1="192" x2="240" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="80" y1="64" x2="16" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="80" y1="192" x2="16" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><rect x="16" y="64" width="224" height="128" rx="8" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><circle cx="128" cy="128" r="32" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="176" y1="64" x2="240" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="176" y1="192" x2="240" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="80" y1="64" x2="16" y2="120" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="80" y1="192" x2="16" y2="136" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
