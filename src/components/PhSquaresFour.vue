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
      <rect
        x="48"
        y="48"
        width="60"
        height="60"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="148"
        y="48"
        width="60"
        height="60"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="48"
        y="148"
        width="60"
        height="60"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="148"
        y="148"
        width="60"
        height="60"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <rect x="48" y="48" width="64" height="64" opacity="0.2" />
      <rect x="144" y="48" width="64" height="64" opacity="0.2" />
      <rect x="48" y="144" width="64" height="64" opacity="0.2" />
      <rect x="144" y="144" width="64" height="64" opacity="0.2" />
      <rect
        x="144"
        y="144"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="48"
        y="48"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="48"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="48"
        y="144"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <g>
        <rect x="40" y="40" width="80" height="80" rx="8" />
        <rect x="136" y="40" width="80" height="80" rx="8" />
        <rect x="40" y="136" width="80" height="80" rx="8" />
        <rect x="136" y="136" width="80" height="80" rx="8" />
      </g>
    </g>
    <g v-else-if="displayWeight === 'light'">
      <rect
        x="48"
        y="48"
        width="64"
        height="64"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="48"
        width="64"
        height="64"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="48"
        y="144"
        width="64"
        height="64"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="144"
        width="64"
        height="64"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <rect
        x="48"
        y="48"
        width="64"
        height="64"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="48"
        width="64"
        height="64"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="48"
        y="144"
        width="64"
        height="64"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="144"
        width="64"
        height="64"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <rect
        x="48"
        y="48"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="48"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="48"
        y="144"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="144"
        y="144"
        width="64"
        height="64"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
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
  name: "PhSquaresFour",
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
