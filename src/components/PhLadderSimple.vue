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
    <g v-if="weight === 'bold'"><line x1="64" y1="32" x2="64" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="192" y1="32" x2="192" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="64" y1="72" x2="192" y2="72" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="64" y1="128" x2="192" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="64" y1="184" x2="192" y2="184" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><line x1="64" y1="32" x2="64" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="192" y1="32" x2="192" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="64" y1="72" x2="192" y2="72" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="64" y1="128" x2="192" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="64" y1="184" x2="192" y2="184" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M192,24a8,8,0,0,0-8,8V64H72V32a8,8,0,0,0-16,0V224a8,8,0,0,0,16,0V192H184v32a8,8,0,0,0,16,0V32A8,8,0,0,0,192,24Zm-8,56v40H72V80ZM72,176V136H184v40Z"/></g>
    <g v-else-if="weight === 'light'"><line x1="64" y1="32" x2="64" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="192" y1="32" x2="192" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="64" y1="72" x2="192" y2="72" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="64" y1="128" x2="192" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="64" y1="184" x2="192" y2="184" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><line x1="64" y1="32" x2="64" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="192" y1="32" x2="192" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="64" y1="72" x2="192" y2="72" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="64" y1="128" x2="192" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="64" y1="184" x2="192" y2="184" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><line x1="64" y1="32" x2="64" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="192" y1="32" x2="192" y2="224" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="64" y1="72" x2="192" y2="72" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="64" y1="128" x2="192" y2="128" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="64" y1="184" x2="192" y2="184" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
