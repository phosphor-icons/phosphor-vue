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
      <polyline
        points="148 32 148 92 208.008 92"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M72,224.00005H55.99219a8,8,0,0,1-8-8V184"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <polyline
        points="120 32 152 32 208 88 208 136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M47.99219,64V40a8,8,0,0,1,8-8L80,32"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M208,176v40a8,8,0,0,1-8,8h-8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="48"
        y1="104"
        x2="48"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="112"
        y1="224"
        x2="152"
        y2="224"
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
        d="M72,224.00005H55.99219a8,8,0,0,1-8-8V184"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <polyline
        points="120 32 152 32 208 88 208 136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M47.99219,64V40a8,8,0,0,1,8-8L80,32"
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
      <path
        d="M208,176v40a8,8,0,0,1-8,8h-8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="48"
        y1="104"
        x2="48"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="112"
        y1="224"
        x2="152"
        y2="224"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M80,224a8.00039,8.00039,0,0,1-8,8H55.99219a16.01833,16.01833,0,0,1-16-16V184a8,8,0,0,1,16,0v32H72A8.00039,8.00039,0,0,1,80,224ZM80,24H55.99219a16.01833,16.01833,0,0,0-16,16V64a8,8,0,0,0,16,0V40H80a8,8,0,0,0,0-16ZM216.00781,88a7.9698,7.9698,0,0,0-2.4248-5.731L157.65723,26.34277c-.0542-.05407-.11426-.10089-.16944-.15326-.1333-.126-.26611-.25268-.4082-.36932-.06738-.05566-.14014-.10364-.20947-.15686-.13819-.1062-.27539-.21356-.41992-.31079-.05811-.03882-.11963-.07129-.17872-.10858-.1621-.10279-.3247-.20478-.49462-.2959-.04248-.02271-.08692-.04059-.12989-.0625-.18945-.09747-.38135-.19141-.57959-.2738-.02832-.01191-.05859-.02045-.0874-.03205-.2124-.08539-.42725-.16492-.64844-.23218-.02978-.00909-.06054-.01452-.09033-.02325-.21875-.06384-.43994-.12225-.666-.16742-.07032-.0141-.14209-.0202-.21241-.03241-.18652-.032-.373-.06518-.564-.08411A7.98793,7.98793,0,0,0,152,24H120a8,8,0,0,0,0,16h24V88a8.00039,8.00039,0,0,0,8,8h48v40a8,8,0,0,0,16,0V88.15942C216.001,88.106,216.00781,88.05383,216.00781,88ZM208,168a8.00039,8.00039,0,0,0-8,8v40h-8a8,8,0,0,0,0,16h8a16.01833,16.01833,0,0,0,16-16V176A8.00039,8.00039,0,0,0,208,168ZM48,152a8.00039,8.00039,0,0,0,8-8V104a8,8,0,0,0-16,0v40A8.00039,8.00039,0,0,0,48,152Zm104,64H112a8,8,0,0,0,0,16h40a8,8,0,0,0,0-16Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M72,224.00005H55.99219a8,8,0,0,1-8-8V184"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <polyline
        points="120 32 152 32 208 88 208 136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M47.99219,64V40a8,8,0,0,1,8-8L80,32"
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
      <path
        d="M208,176v40a8,8,0,0,1-8,8h-8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="48"
        y1="104"
        x2="48"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="112"
        y1="224"
        x2="152"
        y2="224"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M72,224.00005H55.99219a8,8,0,0,1-8-8V184"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <polyline
        points="120 32 152 32 208 88 208 136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M47.99219,64V40a8,8,0,0,1,8-8L80,32"
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
      <path
        d="M208,176v40a8,8,0,0,1-8,8h-8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="48"
        y1="104"
        x2="48"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="112"
        y1="224"
        x2="152"
        y2="224"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M72,224.00005H55.99219a8,8,0,0,1-8-8V184"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <polyline
        points="120 32 152 32 208 88 208 136"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M47.99219,64V40a8,8,0,0,1,8-8L80,32"
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
      <path
        d="M208,176v40a8,8,0,0,1-8,8h-8"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="48"
        y1="104"
        x2="48"
        y2="144"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="112"
        y1="224"
        x2="152"
        y2="224"
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
  name: "PhFileDotted",
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
