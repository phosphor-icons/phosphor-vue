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
        d="M156.21732,219.78606a95.898,95.898,0,1,1,63.57-63.573Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <circle cx="92" cy="108" r="16" />
      <circle cx="164" cy="108" r="16" />
      <path
        d="M169.58,151.99735a48.016,48.016,0,0,1-83.15966.00055"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M156.21732,219.78606a95.898,95.898,0,1,1,63.57-63.573Z"
        opacity="0.2"
      />
      <path
        d="M156.21732,219.78606a95.898,95.898,0,1,1,63.57-63.573Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle cx="92" cy="108" r="12" />
      <circle cx="164" cy="108" r="12" />
      <path
        d="M169.58,151.99735a48.016,48.016,0,0,1-83.15966.00055"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M128,24a104,104,0,1,0,30.56543,203.43359,7.99683,7.99683,0,0,0,3.30859-1.99072l63.57032-63.57324a7.99548,7.99548,0,0,0,1.99072-3.30859A104.07559,104.07559,0,0,0,128,24Zm36,72a12,12,0,1,1-12,12A12,12,0,0,1,164,96ZM92,96a12,12,0,1,1-12,12A12,12,0,0,1,92,96Zm84.50488,60.00269a56.01585,56.01585,0,0,1-97.00976.00048,8.00016,8.00016,0,0,1,13.85058-8.01074,40.016,40.016,0,0,0,69.30957-.00049,7.99975,7.99975,0,1,1,13.84961,8.01075Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M156.21732,219.78606a95.898,95.898,0,1,1,63.57-63.573Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <circle cx="92" cy="108" r="10" />
      <circle cx="164" cy="108" r="10" />
      <path
        d="M169.58,151.99735a48.016,48.016,0,0,1-83.15966.00055"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M156.21732,219.78606a95.898,95.898,0,1,1,63.57-63.573Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <circle cx="92" cy="108" r="8" />
      <circle cx="164" cy="108" r="8" />
      <path
        d="M169.58,151.99735a48.016,48.016,0,0,1-83.15966.00055"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M156.21732,219.78606a95.898,95.898,0,1,1,63.57-63.573Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle cx="92" cy="108" r="12" />
      <circle cx="164" cy="108" r="12" />
      <path
        d="M169.58,151.99735a48.016,48.016,0,0,1-83.15966.00055"
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
  name: "PhSmileySticker",
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
