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
        d="M208,144c0-72-80-128-80-128S48,72,48,144a80,80,0,0,0,160,0Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="128"
        y1="224"
        x2="128"
        y2="16"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="127.99999"
        y1="79.99999"
        x2="206.65864"
        y2="158.65864"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="127.99999"
        y1="139.99999"
        x2="186.53165"
        y2="198.53165"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path d="M128,224a80,80,0,0,0,80-80c0-72-80-128-80-128Z" opacity="0.2" />
      <path
        d="M208,144c0-72-80-128-80-128S48,72,48,144a80,80,0,0,0,160,0Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="128"
        y1="224"
        x2="128"
        y2="16"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M208,144c0-72-80-128-80-128S48,72,48,144a80,80,0,0,0,160,0Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path d="M128,224a80,80,0,0,0,80-80c0-72-80-128-80-128Z" />
      <line
        x1="128"
        y1="224"
        x2="128"
        y2="16"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M208,144c0-72-80-128-80-128S48,72,48,144a80,80,0,0,0,160,0Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="128"
        y1="224"
        x2="128"
        y2="16"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="127.99999"
        y1="63.99999"
        x2="208"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="127.99999"
        y1="111.99999"
        x2="198.26945"
        y2="182.26945"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <g>
        <line
          x1="127.99999"
          y1="159.99999"
          x2="176.00281"
          y2="208.00281"
          fill="none"
          :stroke="displayColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="12"
        />
        <line
          x1="127.99999"
          y1="159.99999"
          x2="176.00281"
          y2="208.00281"
          fill="#231f20"
        />
      </g>
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M208,144c0-72-80-128-80-128S48,72,48,144a80,80,0,0,0,160,0Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="128"
        y1="224"
        x2="128"
        y2="16"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="127.99999"
        y1="63.99999"
        x2="208"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="127.99999"
        y1="111.99999"
        x2="198.26945"
        y2="182.26945"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <g>
        <line
          x1="127.99999"
          y1="159.99999"
          x2="176.00281"
          y2="208.00281"
          fill="none"
          :stroke="displayColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="8"
        />
        <line
          x1="127.99999"
          y1="159.99999"
          x2="176.00281"
          y2="208.00281"
          fill="#231f20"
        />
      </g>
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M208,144c0-72-80-128-80-128S48,72,48,144a80,80,0,0,0,160,0Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="128"
        y1="224"
        x2="128"
        y2="16"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="127.99999"
        y1="63.99999"
        x2="208"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="127.99999"
        y1="111.99999"
        x2="198.26945"
        y2="182.26945"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <g>
        <line
          x1="127.99999"
          y1="159.99999"
          x2="176.00281"
          y2="208.00281"
          fill="none"
          :stroke="displayColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="16"
        />
        <line
          x1="127.99999"
          y1="159.99999"
          x2="176.00281"
          y2="208.00281"
          fill="#231f20"
        />
      </g>
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
  name: "PhDropHalf",
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
