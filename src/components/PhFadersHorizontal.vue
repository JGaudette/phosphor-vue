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
    <g v-if="weight === 'bold'"><line x1="132" y1="172" x2="40" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="216" y1="172" x2="172" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="68" y1="84" x2="40" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="216" y1="84" x2="108" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="108" y1="60" x2="108" y2="108" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="172" y1="196" x2="172" y2="148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><line x1="136" y1="172" x2="40" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="216" y1="172" x2="168" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="72" y1="84" x2="40" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="216" y1="84" x2="104" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="104" y1="60" x2="104" y2="108" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="168" y1="196" x2="168" y2="148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M136,164H40a8,8,0,0,0,0,16h96a8,8,0,0,0,0-16Z"/><path d="M216,164H176V148a8,8,0,0,0-16,0v48a8,8,0,0,0,16,0V180h40a8,8,0,0,0,0-16Z"/><path d="M40,92H72a8,8,0,0,0,0-16H40a8,8,0,0,0,0,16Z"/><path d="M104,116a8,8,0,0,0,8-8V92H216a8,8,0,0,0,0-16H112V60a8,8,0,0,0-16,0v48A8,8,0,0,0,104,116Z"/></g>
    <g v-else-if="weight === 'light'"><line x1="136" y1="172" x2="40" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="216" y1="172" x2="168" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="72" y1="84" x2="40" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="216" y1="84" x2="104" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="104" y1="60" x2="104" y2="108" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="168" y1="196" x2="168" y2="148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><line x1="136" y1="172" x2="40" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="216" y1="172" x2="168" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="72" y1="84" x2="40" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="216" y1="84" x2="104" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="104" y1="60" x2="104" y2="108" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="168" y1="196" x2="168" y2="148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><line x1="136" y1="172" x2="40" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="216" y1="172" x2="168" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="72" y1="84" x2="40" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="216" y1="84" x2="104" y2="84" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="104" y1="60" x2="104" y2="108" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="168" y1="196" x2="168" y2="148" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
