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
        d="M200.00039,224H55.99961A7.99981,7.99981,0,0,1,48,216V40a7.99981,7.99981,0,0,1,7.99961-8l96.00312,0L208,88V216A7.99981,7.99981,0,0,1,200.00039,224Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <polyline
        points="148 32 148 92 208.008 92"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <polygon points="152 32 152 88 208.008 88 152 32" opacity="0.2" />
      <path
        d="M200.00039,224H55.99961A7.99981,7.99981,0,0,1,48,216V40a7.99981,7.99981,0,0,1,7.99961-8l96.00312,0L208,88V216A7.99981,7.99981,0,0,1,200.00039,224Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <polyline
        points="152 32 152 88 208.008 88"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M213.58936,82.2749,157.65723,26.34277c-.08008-.08007-.167-.15039-.25-.22656-.10791-.09912-.21289-.20166-.32618-.29492-.07519-.06152-.15576-.11524-.23291-.17432-.13085-.10009-.26025-.20166-.397-.29394-.062-.04151-.12793-.07617-.19043-.11573-.15869-.10009-.31738-.1997-.4834-.28906-.04492-.02392-.09179-.04248-.13672-.06543-.1875-.09668-.377-.18945-.57275-.271-.03027-.0127-.0625-.022-.09326-.03418-.21045-.08448-.42383-.16358-.64258-.23-.03174-.00977-.06445-.01563-.09619-.02491-.2168-.063-.436-.12109-.66064-.166-.07129-.01416-.145-.02051-.2168-.03272-.18555-.03222-.37012-.06494-.55908-.08349A7.91349,7.91349,0,0,0,152,24H55.99219a16.01833,16.01833,0,0,0-16,16V216a16.01833,16.01833,0,0,0,16,16H200a16.01833,16.01833,0,0,0,16-16V88.15479c.001-.05225.00781-.10254.00781-.15479A7.97147,7.97147,0,0,0,213.58936,82.2749ZM152,88V43.31348L196.68555,88Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M200.00039,224H55.99961A7.99981,7.99981,0,0,1,48,216V40a7.99981,7.99981,0,0,1,7.99961-8l96.00312,0L208,88V216A7.99981,7.99981,0,0,1,200.00039,224Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <polyline
        points="152 32 152 88 208.008 88"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M200.00039,224H55.99961A7.99981,7.99981,0,0,1,48,216V40a7.99981,7.99981,0,0,1,7.99961-8l96.00312,0L208,88V216A7.99981,7.99981,0,0,1,200.00039,224Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <polyline
        points="152 32 152 88 208.008 88"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M200.00039,224H55.99961A7.99981,7.99981,0,0,1,48,216V40a7.99981,7.99981,0,0,1,7.99961-8l96.00312,0L208,88V216A7.99981,7.99981,0,0,1,200.00039,224Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <polyline
        points="152 32 152 88 208.008 88"
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
  name: "PhFile",
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
