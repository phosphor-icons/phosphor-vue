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
      <line
        x1="100"
        y1="12"
        x2="156"
        y2="12"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <rect
        x="56.00586"
        y="48"
        width="144"
        height="180"
        rx="16"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <polyline
        points="128 178 144 138 112 138 128 98"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <rect x="56" y="40" width="144" height="184" rx="16" opacity="0.2" />
      <line
        x1="96"
        y1="8"
        x2="160"
        y2="8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <rect
        x="56"
        y="40"
        width="144"
        height="184"
        rx="16"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <polyline
        points="128 172 144 132 112 132 128 92"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <g>
        <path d="M96,16h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16Z" />
        <path
          d="M184,32.00781H72a24.02625,24.02625,0,0,0-24,24v152a24.02624,24.02624,0,0,0,24,24H184a24.02624,24.02624,0,0,0,24-24v-152A24.02624,24.02624,0,0,0,184,32.00781ZM151.42969,134.97656l-16,40a8.00086,8.00086,0,0,1-14.85938-5.9375l11.61719-29.03125L112,139.99219a8.001,8.001,0,0,1-7.42969-10.96875l16-39.98438a8.00086,8.00086,0,0,1,14.85938,5.9375L123.8125,123.99219,144,124.00781a8.001,8.001,0,0,1,7.42969,10.96875Z"
        />
      </g>
    </g>
    <g v-else-if="displayWeight === 'light'">
      <line
        x1="96"
        y1="8"
        x2="160"
        y2="8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <rect
        x="56"
        y="40"
        width="144"
        height="184"
        rx="16"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <polyline
        points="128 172 144 132 112 132 128 92"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <line
        x1="96"
        y1="8"
        x2="160"
        y2="8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <rect
        x="56"
        y="40"
        width="144"
        height="184"
        rx="16"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <polyline
        points="128 172 144 132 112 132 128 92"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <line
        x1="96"
        y1="8"
        x2="160"
        y2="8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <rect
        x="56"
        y="40"
        width="144"
        height="184"
        rx="16"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <polyline
        points="128 172 144 132 112 132 128 92"
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
  name: "PhBatteryChargingVertical",
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
