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
      <ellipse
        cx="128"
        cy="104"
        rx="104"
        ry="48"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="128"
        y1="152"
        x2="128"
        y2="200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M24,104v48c0,24,40,48,104,48s104-24,104-48V104"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="192"
        y1="142.10679"
        x2="192"
        y2="190.10744"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="64"
        y1="142.10679"
        x2="64"
        y2="190.10721"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <ellipse cx="128" cy="104" rx="104" ry="48" opacity="0.2" />
      <ellipse
        cx="128"
        cy="104"
        rx="104"
        ry="48"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="128"
        y1="152"
        x2="128"
        y2="200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M24,104v48c0,24,40,48,104,48s104-24,104-48V104"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="192"
        y1="142.10679"
        x2="192"
        y2="190.10744"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="64"
        y1="142.10679"
        x2="64"
        y2="190.10721"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M207.57812,63.84473C186.84668,53.47852,159.3291,48,128,48S69.15332,53.47852,48.42188,63.84473C27.81738,74.14746,16,88.7832,16,104v48c0,15.2168,11.81738,29.85254,32.42188,40.15527C69.15332,202.52148,96.6709,208,128,208s58.84668-5.47852,79.57812-15.84473C228.18262,181.85254,240,167.2168,240,152V104C240,88.7832,228.18262,74.14746,207.57812,63.84473ZM120,159.86328V191.855c-18.98486-.62207-35.02637-3.42822-48-7.49414V153.04541A203.76361,203.76361,0,0,0,120,159.86328Zm16,0a203.76361,203.76361,0,0,0,48-6.81787v31.31543c-12.97363,4.06592-29.01514,6.87207-48,7.49414ZM32,152V133.53076a82.6098,82.6098,0,0,0,16.42188,10.62451c2.43164,1.21582,4.96484,2.3584,7.57812,3.43848v30.43359C40.17334,170.16455,32,160.294,32,152Zm168,26.02734V147.59375c2.61328-1.08008,5.14648-2.22266,7.57812-3.43848A82.6098,82.6098,0,0,0,224,133.53076V152C224,160.294,215.82666,170.16455,200,178.02734Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <ellipse
        cx="128"
        cy="104"
        rx="104"
        ry="48"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="128"
        y1="152"
        x2="128"
        y2="200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M24,104v48c0,24,40,48,104,48s104-24,104-48V104"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="192"
        y1="142.10679"
        x2="192"
        y2="190.10744"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="64"
        y1="142.10679"
        x2="64"
        y2="190.10721"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <ellipse
        cx="128"
        cy="104"
        rx="104"
        ry="48"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="128"
        y1="152"
        x2="128"
        y2="200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M24,104v48c0,24,40,48,104,48s104-24,104-48V104"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="192"
        y1="142.10679"
        x2="192"
        y2="190.10744"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="64"
        y1="142.10679"
        x2="64"
        y2="190.10721"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <ellipse
        cx="128"
        cy="104"
        rx="104"
        ry="48"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="128"
        y1="152"
        x2="128"
        y2="200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M24,104v48c0,24,40,48,104,48s104-24,104-48V104"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="192"
        y1="142.10679"
        x2="192"
        y2="190.10744"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="64"
        y1="142.10679"
        x2="64"
        y2="190.10721"
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
  name: "PhCoin",
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
