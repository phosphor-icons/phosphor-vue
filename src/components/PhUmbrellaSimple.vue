/* GENERATED FILE */
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 256 256"
    :width="displaySize"
    :height="displaySize"
    :fill="displayColor"
    :transform="displayMirrored"
    v-bind="$attrs"
    v-on="$listeners"
  >
    <slot />
    <g v-if="displayWeight === 'bold'">
      <path
        d="M176,200a24,24,0,0,1-48,0V136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M32.33457,136a8.021,8.021,0,0,1-7.97506-8.70945,104.00633,104.00633,0,0,1,207.281,0A8.021,8.021,0,0,1,223.66543,136Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M32.33457,136a8.021,8.021,0,0,1-7.97506-8.70945,104.00633,104.00633,0,0,1,207.281,0A8.021,8.021,0,0,1,223.66543,136Z"
        opacity="0.2"
      />
      <path
        d="M176,200a24,24,0,0,1-48,0V136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M32.33457,136a8.021,8.021,0,0,1-7.97506-8.70945,104.00633,104.00633,0,0,1,207.281,0A8.021,8.021,0,0,1,223.66543,136Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M235.42676,138.83984A16.02871,16.02871,0,0,1,223.66553,144H136v56a16,16,0,0,0,32,0,8,8,0,0,1,16,0,32,32,0,0,1-64,0V144H32.33447a16.02123,16.02123,0,0,1-15.94775-17.37012,112.00665,112.00665,0,0,1,223.22656,0A16.11107,16.11107,0,0,1,235.42676,138.83984Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M176,200a24,24,0,0,1-48,0V136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M32.33457,136a8.021,8.021,0,0,1-7.97506-8.70945,104.00633,104.00633,0,0,1,207.281,0A8.021,8.021,0,0,1,223.66543,136Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M176,200a24,24,0,0,1-48,0V136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M32.33457,136a8.021,8.021,0,0,1-7.97506-8.70945,104.00633,104.00633,0,0,1,207.281,0A8.021,8.021,0,0,1,223.66543,136Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M176,200a24,24,0,0,1-48,0V136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M32.33457,136a8.021,8.021,0,0,1-7.97506-8.70945,104.00633,104.00633,0,0,1,207.281,0A8.021,8.021,0,0,1,223.66543,136Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
  </svg>
</template>

<script lang="ts">
import Vue from "vue";
import {
  IconComputed,
  IconProps,
  PropValidator,
  IconContext,
  ContextGetter
} from "@/lib/types";
export default Vue.extend<{}, {}, IconComputed, IconProps>({
  name: "PhUmbrellaSimple",
  props: PropValidator,
  inject: ContextGetter,
  computed: {
    displayWeight() {
      const { weight, contextWeight } = this as IconProps & IconContext;
      return weight ?? contextWeight;
    },
    displaySize() {
      const { size, contextSize } = this as IconProps & IconContext;
      return size ?? contextSize;
    },
    displayColor() {
      const { color, contextColor } = this as IconProps & IconContext;
      return color ?? contextColor;
    },
    displayMirrored() {
      const { mirrored, contextMirrored } = this as IconProps & IconContext;
      return mirrored ?? contextMirrored ? "scale(-1, 1)" : undefined;
    }
  }
});
</script>
