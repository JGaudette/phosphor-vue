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
    <g v-if="weight === 'bold'"><polyline points="48 152 48 216 208 216 208 152" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="88" y1="172" x2="168" y2="172" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="100.3" y1="102.2" x2="175.5" y2="129.6" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="135.7" y1="40.9" x2="197" y2="92.3" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></g>
    <g v-else-if="weight === 'duotone'"><polyline points="48 152 48 216 208 216 208 152" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="88" y1="176" x2="168" y2="176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="95" y1="123.2" x2="172.2" y2="143.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="115.3" y1="74" x2="184.6" y2="114" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="147.8" y1="31.8" x2="204.3" y2="88.3" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
    <g v-else-if="weight === 'fill'"><path d="M216,152v64a8,8,0,0,1-8,8H48a8,8,0,0,1-8-8V152a8,8,0,0,1,16,0v56H200V152a8,8,0,0,1,16,0ZM88,184h80a8,8,0,0,0,0-16H88a8,8,0,0,0,0,16Zm4.9-53.1,77.3,20.7a6.4,6.4,0,0,0,2,.3,8,8,0,0,0,2.1-15.7L97,115.5a8,8,0,1,0-4.1,15.4Zm18.4-50,69.3,40a7.3,7.3,0,0,0,4,1.1,7.7,7.7,0,0,0,6.9-4,7.9,7.9,0,0,0-2.9-10.9l-69.3-40a8,8,0,0,0-8,13.8ZM198.7,94a8,8,0,0,0,5.6,2.3A8.3,8.3,0,0,0,210,94a8,8,0,0,0,0-11.3L153.4,26.1a8,8,0,0,0-11.3,11.3Z"/></g>
    <g v-else-if="weight === 'light'"><polyline points="48 152 48 216 208 216 208 152" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="88" y1="176" x2="168" y2="176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="95" y1="123.2" x2="172.2" y2="143.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="115.3" y1="74" x2="184.6" y2="114" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/><line x1="147.8" y1="31.8" x2="204.3" y2="88.3" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="12"/></g>
    <g v-else-if="weight === 'thin'"><polyline points="48 152 48 216 208 216 208 152" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="88" y1="176" x2="168" y2="176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="95" y1="123.2" x2="172.2" y2="143.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="115.3" y1="74" x2="184.6" y2="114" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/><line x1="147.8" y1="31.8" x2="204.3" y2="88.3" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="8"/></g>
    <g v-else-if="weight === 'regular'"><polyline points="48 152 48 216 208 216 208 152" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="88" y1="176" x2="168" y2="176" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="95" y1="123.2" x2="172.2" y2="143.9" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="115.3" y1="74" x2="184.6" y2="114" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/><line x1="147.8" y1="31.8" x2="204.3" y2="88.3" fill="none" :stroke="color" stroke-linecap="round" stroke-linejoin="round" stroke-width="16"/></g>
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
