### Documentation

These are the modules that you can customize in the `sasslys/config` file:

- [**Spacing**:](#spacing) Customize the spacing scale for consistent layout and design.
- [**Colors**:](#colors) Define your project's color palette for cohesive styling.
- [**Border radius**:](#border-radius) Set the border radius values for rounded corners.
- [**Font scale**:](#font-scale) Adjust the font size scale for responsive typography.
- [**Motion**:](#motion) Configure motion settings for animations and transitions.
- [**Shadows**:](#shadows) Define shadow styles for depth and emphasis in your design.
- [**Spacing**:](#spacing) Customize the spacing scale for consistent layout and design.
- [**Z-index**:](#z-index) Set the z-index values for layering and stacking elements.
- [**Blur**:](#blur) Configure blur effects for elements to create depth and focus.

In utility helpers:

- [**Breakpoints**:](#breakpoints) Define responsive breakpoints for different screen sizes.
- [**Font faces**:](#font-faces) Set up font families for your project.
- [**Font Weights**:](#font-weights) Define the font weights for different text elements.

For classes, predefined styles and animations, you can check the [**Classes**](#classes) section in the documentation.


<h4 id="spacing">Spacing</h4>

The defined variables for spacing are:

```scss
$spacing_1: 0.1rem;
$spacing_2: 0.2rem;
$spacing_3: 0.3rem;
$spacing_4: 0.4rem;
$spacing_5: 0.5rem;
$spacing_6: 0.6rem;
$spacing_7: 0.7rem;
$spacing_8: 0.8rem;
$spacing_12: 1.2rem;
$spacing_16: 1.6rem;
$spacing_20: 2rem;
$spacing_24: 2.4rem;
$spacing_28: 2.8rem;
$spacing_32: 3.2rem;
$spacing_34: 3.4rem;
$spacing_36: 3.6rem;
$spacing_40: 4rem;
$spacing_44: 4.4rem;
$spacing_48: 4.8rem;
$spacing_56: 5.6rem;
$spacing_64: 6.4rem;
$spacing_80: 8rem;
$spacing_96: 9.6rem;
$spacing_112: 11.2rem;
$spacing_128: 12.8rem;
$spacing_144: 14.4rem;
$spacing_160: 16rem;
$spacing_176: 17.6rem;
$spacing_196: 19.6rem;
$spacing_208: 20.8rem;
$spacing_224: 22.4rem;
$spacing_240: 24rem;
$spacing_256: 25.6rem;
$spacing_288: 28.8rem;
$spacing_320: 32rem;
$spacing_384: 38.4rem;
```

<h4 id="colors">Colors</h4>

The defined variables for colors are:

```scss
$black: #000;
$white: #fff;
$transparent: rgba($black, 0);
$modal: rgba($black, 0.5);

$gray_950: #030712;
$gray_900: #111827;
$gray_800: #1f2937;
$gray_700: #374151;
$gray_600: #4b5563;
$gray_500: #6b7280;
$gray_400: #9ca3af;
$gray_300: #d1d5db;
$gray_200: #e5e7eb;
$gray_100: #f3f4f6;
$gray_50: #f9fafb;

$neutral_950: #0a0a0a;
$neutral_900: #171717;
$neutral_800: #262626;
$neutral_700: #404040;
$neutral_600: #525252;
$neutral_500: #737373;
$neutral_400: #a3a3a3;
$neutral_300: #d4d4d4;
$neutral_200: #e5e5e5;
$neutral_100: #f5f5f5;
$neutral_50: #fafafa;

$success_950: #052e16;
$success_900: #14532d;
$success_800: #166534;
$success_700: #15803d;
$success_600: #16a34a;
$success_500: #22c55e;
$success_400: #4ade80;
$success_300: #86efac;
$success_200: #bbf7d0;
$success_100: #dcfce7;
$success_50: #f0fdf4;

$warning_950: #422006;
$warning_900: #713f12;
$warning_800: #854d0e;
$warning_700: #a16207;
$warning_600: #ca8a04;
$warning_500: #eab308;
$warning_400: #facc15;
$warning_300: #fde047;
$warning_200: #fef08a;
$warning_100: #fef9c3;
$warning_50: #fefce8;

$danger_950: #450a0a;
$danger_900: #7f1d1d;
$danger_800: #991b1b;
$danger_700: #b91c1c;
$danger_600: #dc2626;
$danger_500: #ef4444;
$danger_400: #f87171;
$danger_300: #fca5a5;
$danger_200: #fecaca;
$danger_100: #fee2e2;
$danger_50: #fef2f2;

$information_950: #172554;
$information_900: #1e3a8a;
$information_800: #1e40af;
$information_700: #1d4ed8;
$information_600: #2563eb;
$information_500: #3b82f6;
$information_400: #60a5fa;
$information_300: #93c5fd;
$information_200: #bfdbfe;
$information_100: #dbeafe;
$information_50: #eff6ff;

$slate_950: #020617;
$slate_900: #0f172a;
$slate_800: #1e293b;
$slate_700: #334155;
$slate_600: #475569;
$slate_500: #64748b;
$slate_400: #94a3b8;
$slate_300: #cbd5e1;
$slate_200: #e2e8f0;
$slate_100: #f1f5f9;
$slate_50: #f8fafc;

$zinc_950: #09090b;
$zinc_900: #18181b;
$zinc_800: #27272a;
$zinc_700: #3f3f46;
$zinc_600: #52525b;
$zinc_500: #71717a;
$zinc_400: #a1a1aa;
$zinc_300: #d4d4d8;
$zinc_200: #e4e4e7;
$zinc_100: #f4f4f5;
$zinc_50: #fafafa;

$stone_950: #0c0a09;
$stone_900: #1c1917;
$stone_800: #292524;
$stone_700: #44403c;
$stone_600: #57534e;
$stone_500: #78716c;
$stone_400: #a8a29e;
$stone_300: #d6d3d1;
$stone_200: #e7e5e4;
$stone_100: #f5f5f4;
$stone_50: #fafaf9;

$orange_950: #431407;
$orange_900: #7c2d12;
$orange_800: #9a3412;
$orange_700: #c2410c;
$orange_600: #ea580c;
$orange_500: #f97316;
$orange_400: #fb923c;
$orange_300: #fdba74;
$orange_200: #fed7aa;
$orange_100: #ffedd5;
$orange_50: #fff7ed;

$amber_950: #451a03;
$amber_900: #78350f;
$amber_800: #92400e;
$amber_700: #b45309;
$amber_600: #d97706;
$amber_500: #eab308;
$amber_400: #fbbf24;
$amber_300: #fcd34d;
$amber_200: #fde68a;
$amber_100: #fef3c7;
$amber_50: #fffbeb;

$lime_950: #1a2e05;
$lime_900: #365314;
$lime_800: #3f6212;
$lime_700: #4d7c0f;
$lime_600: #65a30d;
$lime_500: #84cc16;
$lime_400: #a3e635;
$lime_300: #bef264;
$lime_200: #d9f99d;
$lime_100: #ecfccb;
$lime_50: #f7fee7;

$emerald_950: #022c22;
$emerald_900: #064e3b;
$emerald_800: #065f46;
$emerald_700: #047857;
$emerald_600: #059669;
$emerald_500: #10b981;
$emerald_400: #34d399;
$emerald_300: #6ee7b7;
$emerald_200: #a7f3d0;
$emerald_100: #d1fae5;
$emerald_50: #ecfdf5;

$teal_950: #042f2e;
$teal_900: #134e4a;
$teal_800: #115e59;
$teal_700: #0f766e;
$teal_600: #0d9488;
$teal_500: #14b8a6;
$teal_400: #2dd4bf;
$teal_300: #5eead4;
$teal_200: #99f6e4;
$teal_100: #ccfbf1;
$teal_50: #f0fdfa;

$cyan_950: #083344;
$cyan_900: #164e63;
$cyan_800: #155e75;
$cyan_700: #0e7490;
$cyan_600: #0891b2;
$cyan_500: #06b6d4;
$cyan_400: #22d3ee;
$cyan_300: #67e8f9;
$cyan_200: #a5f3fc;
$cyan_100: #cffafe;
$cyan_50: #ecfeff;

$sky_950: #082f49;
$sky_900: #0c4a6e;
$sky_800: #075985;
$sky_700: #0369a1;
$sky_600: #0284c7;
$sky_500: #0ea5e9;
$sky_400: #38bdf8;
$sky_300: #7dd3fc;
$sky_200: #bae6fd;
$sky_100: #e0f2fe;
$sky_50: #f0f9ff;

$indigo_950: #1e1b4b;
$indigo_900: #312e81;
$indigo_800: #3730a3;
$indigo_700: #4338ca;
$indigo_600: #4f46e5;
$indigo_500: #6366f1;
$indigo_400: #818cf8;
$indigo_300: #a5b4fc;
$indigo_200: #c7d2fe;
$indigo_100: #e0e7ff;
$indigo_50: #eef2ff;

$violet_950: #2e1065;
$violet_900: #4c1d95;
$violet_800: #5b21b6;
$violet_700: #6d28d9;
$violet_600: #7c3aed;
$violet_500: #8b5cf6;
$violet_400: #a78bfa;
$violet_300: #c4b5fd;
$violet_200: #ddd6fe;
$violet_100: #ede9fe;
$violet_50: #f5f3ff;

$purple_950: #3b0764;
$purple_900: #581c87;
$purple_800: #6b21a8;
$purple_700: #7e22ce;
$purple_600: #9333ea;
$purple_500: #a855f7;
$purple_400: #c084fc;
$purple_300: #d8b4fe;
$purple_200: #e9d5ff;
$purple_100: #f3e8ff;
$purple_50: #faf5ff;

$fuchsia_950: #4a044e;
$fuchsia_900: #701a75;
$fuchsia_800: #86198f;
$fuchsia_700: #a21caf;
$fuchsia_600: #c026d3;
$fuchsia_500: #d946ef;
$fuchsia_400: #e879f9;
$fuchsia_300: #f0abfc;
$fuchsia_200: #f5d0fe;
$fuchsia_100: #fae8ff;
$fuchsia_50: #fdf4ff;

$pink_950: #500724;
$pink_900: #831843;
$pink_800: #9d174d;
$pink_700: #be185d;
$pink_600: #db2777;
$pink_500: #f472b6;
$pink_400: #f472b6;
$pink_300: #f9a8d4;
$pink_200: #fbcfe8;
$pink_100: #fce7f3;
$pink_50: #fdf2f8;

$rose_950: #4c0519;
$rose_900: #881337;
$rose_800: #9f1239;
$rose_700: #be123c;
$rose_600: #e11d48;
$rose_500: #f43f5e;
$rose_400: #fb7185;
$rose_300: #fda4af;
$rose_200: #fecdd3;
$rose_100: #ffe4e6;
$rose_50: #fff1f2;
```

<h4 id="border-radius">Border radius</h4>

The defined variables for border radius are:

```scss
$rounded_none: 0;
$rounded_small: 1.2rem;
$rounded_medium: 2rem;
$rounded_large: 3.2rem;
$rounded_max: 999rem;
$rounded_half: 50%;
```

<h4 id="font-scale">Font scale</h4>

The defined variables for font scale are:

```scss
$xl4: 11.64rem;
$xl3: 9.31rem;
$xl2: 7.45rem;
$xl: 5.96rem;
$h1: 4.76rem;
$h2: 3.81rem;
$h3: 3.04rem;
$h4: 2.44rem;
$h5: 1.95rem;
$h6: 1.56rem;
$sm: 1.25rem;
$ss: 1rem;
```

<h4 id="motion">Motion</h4>

The defined variables for motion are:

```scss
$ms_fast: 150ms;
$ms_base: 300ms;
$ms_slow: 500ms;
$ms_animation: 1s;

$ease_in: cubic-bezier(0.4, 0, 1, 1);
$ease_out: cubic-bezier(0, 0, 0.2, 1);
$ease_in_out: cubic-bezier(0.4, 0, 0.2, 1);
```

<h4 id="shadows">Shadows</h4>

The defined variables for shadows are:

```scss
$shadow_down_black_100: 0 0.2rem 2rem 0 rgba($black, 0.05);
$shadow_down_black_200: 0 0.1rem 0.3rem rgba($black, 0.1), 0 0.1rem 0.2rem rgba($black, 0.1);
$shadow_down_black_300: 0 0.4rem 0.6rem rgba($black, 0.1), 0 0.2rem 0.4rem rgba($black, 0.1);
$shadow_down_black_400: 0 1.5rem 1rem rgba($black, 0.1), 0 0.4rem 0.6rem rgba($black, 0.1);
$shadow_down_black_500: 0 2.5rem 2rem rgba($black, 0.1), 0 1rem 0.8rem rgba($black, 0.1);
$shadow_down_black_600: 0 2.5rem 5rem rgba($black, 0.25);

$shadow_up_black_100: 0 -0.2rem 2rem 0 rgba($black, 0.05);
$shadow_up_black_200: 0 -0.1rem 0.3rem rgba($black, 0.1), 0 -0.1rem 0.2rem rgba($black, 0.1);
$shadow_up_black_300: 0 -0.4rem 0.6rem rgba($black, 0.1), 0 -0.2rem 0.4rem rgba($black, 0.1);
$shadow_up_black_400: 0 -1.5rem 1rem rgba($black, 0.1), 0 -0.4rem 0.6rem rgba($black, 0.1);
$shadow_up_black_500: 0 -2.5rem 2rem rgba($black, 0.1), 0 -1rem 0.8rem rgba($black, 0.1);
$shadow_up_black_600: 0 -2.5rem 5rem rgba($black, 0.25);

$shadow_right_black_100: 0.2rem 0 2rem 0 rgba($black, 0.05);
$shadow_right_black_200: 0.1rem 0 0.3rem rgba($black, 0.1), 0.1rem 0 0.2rem rgba($black, 0.1);
$shadow_right_black_300: 0.4rem 0 0.6rem rgba($black, 0.1), 0.2rem 0 0.4rem rgba($black, 0.1);
$shadow_right_black_400: 1.5rem 0 1rem rgba($black, 0.1), 0.4rem 0 0.6rem rgba($black, 0.1);
$shadow_right_black_500: 2.5rem 0 2rem rgba($black, 0.1), 1rem 0 0.8rem rgba($black, 0.1);
$shadow_right_black_600: 2.5rem 0 5rem rgba($black, 0.25);

$shadow_left_black_100: -0.2rem 0 2rem 0 rgba($black, 0.05);
$shadow_left_black_200: -0.1rem 0 0.3rem rgba($black, 0.1), -0.1rem 0 0.2rem rgba($black, 0.1);
$shadow_left_black_300: -0.4rem 0 0.6rem rgba($black, 0.1), -0.2rem 0 0.4rem rgba($black, 0.1);
$shadow_left_black_400: -1.5rem 0 1rem rgba($black, 0.1), -0.4rem 0 0.6rem rgba($black, 0.1);
$shadow_left_black_500: -2.5rem 0 2rem rgba($black, 0.1), -1rem 0 0.8rem rgba($black, 0.1);
$shadow_left_black_600: -2.5rem 0 5rem rgba($black, 0.25);

$shadow_center_black_100: 0 0.2rem 0.2rem 0 rgba($black, 0.05);
$shadow_center_black_200: 0 0.1rem 0.2rem -0.1rem rgba($black, 0.1), 0 0.1rem 0.3rem 0 rgba($black, 0.1);
$shadow_center_black_300: 0 0.2rem 0.4rem -0.2rem rgba($black, 0.1), 0 0.4rem 0.6rem -0.1rem rgba($black, 0.1);
$shadow_center_black_400: 0 0.4rem 0.6rem -0.4rem rgba($black, 0.1), 0 1.5rem 1rem -0.3rem rgba($black, 0.1);
$shadow_center_black_500: 0 1rem 0.8rem -0.6rem rgba($black, 0.1), 0 2.5rem 2rem -0.5rem rgba($black, 0.1);
$shadow_center_black_600: 0 2.5rem 5rem -1.2rem rgba($black, 0.25);
```

<h4 id="z-index">Z-index</h4>

```scss
$z_0: 0;
$z_10: 10;
$z_20: 20;
$z_30: 30;
$z_40: 40;
$z_50: 50;
$z_60: 60;
$z_70: 70;
$z_80: 80;
$z_90: 90;
$z_100: 100;
$z_auto: auto;

$z_below: -1;
$z_base: $z_0;
$z_docked: $z_10;
$z_dropdown: $z_50;
$z_sticky: $z_60;
$z_overlay: $z_80;
$z_modal: $z_90;
$z_popover: $z_100;
```

<h4 id="blur">Blur</h4>

```scss
$blur_100: blur(0.4rem);
$blur_200: blur(0.8rem);
$blur_300: blur(1.2rem);
$blur_400: blur(2rem);
```

### Utility helpers

<h4 id="breakpoints">Breakpoints</h4>

To use the breakpoints utility helper, you can define your custom breakpoints in the `sasslys/config` file. The default breakpoints are:

```scss

.class {
  @include responsive(small_phone) {
    // Styles for small screens and up
    // min-width: 320px
  }

  @include responsive(phone) {
    // Styles for medium screens and up
    // min-width: 480px
  }

  @include responsive(small_tablet) {
    // Styles for large screens and up
    // min-width: 768px
  }

  @include responsive(tablet) {
    // Styles for extra-large screens and up
    // min-width: 1024px
  }

  @include responsive(small_desktop) {
    // Styles for extra-large screens and up
    // min-width: 1280px
  }

  @include responsive(desktop) {
    // Styles for extra-large screens and up
    // min-width: 1440px
  }

  @include responsive(120rem) {
    // Styles for custom breakpoint and up
    // min-width: 120rem
  }
}
```

<h4 id="font-faces">Font faces</h4>

To use the font faces utility helper, you can define your custom font faces in the `sasslys/config` file. The default font faces are:

```scss
@include font_face(
  $name: 'Inter',
  $path: '/asset/font/inter/inter_light',
  $weight: 300,
  $local: 'Inter Light',
  $extension: 'woff2'
);

// Resulting in 

@font-face {
  font-family: 'Inter';
  src: local('Inter Light'), url('/asset/font/inter/inter_light.woff2') format('woff2');
  font-weight: 300;
  font-style: normal;
}
```

<h4 id="font-weights">Font weights</h4>

To use the font weights utility helper, you can define your custom font weights in the `sasslys/config` file. The default font weights are:

Default font weights are:

```scss
$font_weight: (
  'light': 300,
  'regular': 400,
  'medium': 500,
  'semi_bold': 600,
  'bold': 700,
  'extra_bold': 800
);
```

To use the function, you can do it like this:

```scss
.class {
  font-weight: font-weight(light);
  // Resulting in
  // font-weight: 300;
}
```

<h4 id="classes">Classes</h4>

We defined some extra classes for animations and predefined styles. 

- [**Animations**:](#animations) Predefined animation classes for common effects.
- [**Predefined styles**:](#predefined-styles) Utility classes for common styling needs.
- [**Layout**:](#layout) Utility classes for layout and positioning.

#### Helpers

- [**Animation delay**](#animation-delay): Utility classes to set animation delay for elements.
- [**Aspect ratio**](#aspect-ratio): Utility classes to set aspect ratio for elements.
- [**Cursor**](#cursor): Utility classes to set cursor styles for elements.
- [**Display**](#display): Utility classes to set display properties for elements.
- [**Object fit**](#object-fit): Utility classes to set object fit properties for elements.
- [**Opacity**](#opacity): Utility classes to set opacity for elements.
- [**Overflow**](#overflow): Utility classes to set overflow properties for elements.
- [**Pointer events**](#pointer-events): Utility classes to set pointer events for elements.
- [**Position**](#position): Utility classes to set position properties for elements.
- [**Text align**](#text-align): Utility classes to set text alignment for elements
- [**Rotate**](#rotate): Utility classes to set rotation for elements.
- [**Z index**](#z-index): Utility classes to set z-index for elements.

<h4 id="animations">Animations</h4>

The defined classes for animations are:

```scss
.blur 
.blur-down
.blur-up
.blur-left
.blur-right

// Scroll driven animations
.scroll-blur
.scroll-blur-down
.scroll-blur-up
.scroll-blur-left
.scroll-blur-right
```

For fade in: 

```scss
.fade-in
.fade-in-down
.fade-in-up
.fade-in-left
.fade-in-right

// Scroll driven fade in
.scroll-fade-in
.scroll-fade-in-down
.scroll-fade-in-up
.scroll-fade-in-left
.scroll-fade-in-right
```

For slide in:

```scss
.slide-in-down
.slide-in-up
.slide-in-left
.slide-in-right

// Scroll driven slide in
.scroll-slide-in-down
.scroll-slide-in-up
.scroll-slide-in-left
.scroll-slide-in-right
```

For zoom in:

```scss
.zoom-in
.zoom-out
.zoom-in-down
.zoom-in-up
.zoom-in-left
.zoom-in-right

// Scroll driven zoom in
.scroll-zoom-in
.scroll-zoom-out
.scroll-zoom-in-down
.scroll-zoom-in-up
.scroll-zoom-in-left
.scroll-zoom-in-right
```

For text animations:

```scss
.text-in-up
.text-in-down
.text-in-left
.text-in-right

.text-blur
.text-blur-up
.text-blur-down
.text-blur-left
.text-blur-right

// Scroll driven text animations
.scroll-text-in-up
.scroll-text-in-down
.scroll-text-in-left
.scroll-text-in-right

.scroll-text-blur
.scroll-text-blur-up
.scroll-text-blur-down
.scroll-text-blur-left
.scroll-text-blur-right
```
 
For special animations: 

```scss
.pulse-fade-in
.flip-in-x
.flip-in-y
.twister-in-down
.heart-beat
.tada
.float
.jiggle
.sink
.swing-drop-in
.bounce
```

<h4 id="predefined-styles">Predefined styles</h4>

This section includes utility classes for common styling for the start, we use normalize and reset styles, but we also have some extra classes for common styling needs.

Base styles are: 

```scss
html {
  scroll-behavior: smooth;
  scrollbar-gutter: stable;
  width: 100%;
  font-size: 62.5%;
}

body {
  overflow-x: hidden;
  width: 100%;
  min-height: 100vh;
  font-size: $h6;
  line-height: 1.5;
  color: $gray_950;
  background-color: $gray_100;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-weight: font-weight(regular);
}
```

<h4 id="layout">Layout</h4>

The defined classes for layout are:

```scss
.base-layout {
  max-width: 192rem;
  margin: auto;
  padding-right: $spacing_32;
  padding-left: $spacing_32;

  @include responsive(tablet) {
    padding-right: $spacing_48;
    padding-left: $spacing_48;
  }

  @include responsive(small_desktop) {
    padding-right: $spacing_64;
    padding-left: $spacing_64;
  }
}

.section {
  padding-top: $spacing_80;
  padding-bottom: $spacing_80;

  @include responsive(tablet) {
    padding-top: $spacing_128;
    padding-bottom: $spacing_128;
  }

  @include responsive(small_desktop) {
    padding-top: $spacing_160;
    padding-bottom: $spacing_160;
  }
}
```

<h4 id="animation-delay">Animation delay</h4>

Animation delay are classes from `delay-5` to `delay-100` with a step of 5, and also `delay-150`, `delay-200`, `delay-300` and `delay-400`, in miliseconds.

<h4 id="aspect-ratio">Helpers</h4>

<h4 id="aspect-ratio">Aspect ratio</h4>

```scss
.aspect-ratio-1 {
  aspect-ratio: 1 / 1;
}

.aspect-ratio-3-4 {
  aspect-ratio: 3 / 4;
}

.aspect-ratio-4-3 {
  aspect-ratio: 4 / 3;
}

.aspect-ratio-2-3 {
  aspect-ratio: 2 / 3;
}

.aspect-ratio-3-2 {
  aspect-ratio: 3 / 2;
}

.aspect-ratio-16-9 {
  aspect-ratio: 16 / 9;
}

.aspect-ratio-9-16 {
  aspect-ratio: 9 / 16;
}
```

<h4 id="cursor">Cursor</h4>

```scss
.cursor-auto {
  cursor: auto;
}

.cursor-pointer {
  cursor: pointer;
}

.cursor-help {
  cursor: help;
}

.cursor-not-allowed {
  cursor: not-allowed;
}

.cursor-grab {
  cursor: grab;
}

.cursor-grabbing {
  cursor: grabbing;
}

.cursor-zoom-in {
  cursor: zoom-in;
}

.cursor-zoom-out {
  cursor: zoom-out;
}
```

<h4 id="display">Display</h4>

```scss
.block {
  display: block;
}

.inline-block {
  display: inline-block;
}

.inline {
  display: inline;
}

.flex {
  display: flex;
}

.inline-flex {
  display: inline-flex;
}

.table {
  display: table;
}

.inline-table {
  display: inline-table;
}

.table-caption {
  display: table-caption;
}

.table-cell {
  display: table-cell;
}

.table-column {
  display: table-column;
}

.table-column-group {
  display: table-column-group;
}

.table-footer-group {
  display: table-footer-group;
}

.table-header-group {
  display: table-header-group;
}

.table-row-group {
  display: table-row-group;
}

.table-row {
  display: table-row;
}

.flow-root {
  display: flow-root;
}

.grid {
  display: grid;
}

.inline-grid {
  display: inline-grid;
}

.contents {
  display: contents;
}

.list-item {
  display: list-item;
}

.hidden {
  display: hidden;
}
```

<h4 id="object-fit">Object fit</h4>

```scss
.object-contain {
  object-fit: contain;
}

.object-cover {
  object-fit: cover;
}

.object-fill {
  object-fit: fill;
}

.object-none {
  object-fit: none;
}

.object-scale-down {
  object-fit: scale-down;
}
```

<h4 id="opacity">Opacity</h4>

```scss
.opacity-0 {
  opacity: 0;
}

.opacity-5 {
  opacity: 0.05;
}

.opacity-10 {
  opacity: 0.1;
}

.opacity-15 {
  opacity: 0.15;
}

.opacity-20 {
  opacity: 0.2;
}

.opacity-25 {
  opacity: 0.25;
}

.opacity-30 {
  opacity: 0.3;
}

.opacity-35 {
  opacity: 0.35;
}

.opacity-40 {
  opacity: 0.4;
}

.opacity-45 {
  opacity: 0.45;
}

.opacity-50 {
  opacity: 0.5;
}

.opacity-55 {
  opacity: 0.55;
}

.opacity-60 {
  opacity: 0.6;
}

.opacity-65 {
  opacity: 0.65;
}

.opacity-70 {
  opacity: 0.7;
}

.opacity-75 {
  opacity: 0.75;
}

.opacity-80 {
  opacity: 0.8;
}

.opacity-85 {
  opacity: 0.85;
}

.opacity-90 {
  opacity: 0.9;
}

.opacity-95 {
  opacity: 0.95;
}

.opacity-100 {
  opacity: 1;
}
```

<h4 id="overflow">Overflow</h4>

```scss
.auto {
  overflow: auto;
}

.hidden {
  overflow: hidden;
}

.clip {
  overflow: clip;
}

.visible {
  overflow: visible;
}

.scroll {
  overflow: scroll;
}

.x-auto {
  overflow-x: auto;
}

.x-hidden {
  overflow-x: hidden;
}

.x-clip {
  overflow-x: clip;
}

.x-visible {
  overflow-x: visible;
}

.x-scroll {
  overflow-x: scroll;
}

.y-auto {
  overflow-y: auto;
}

.y-hidden {
  overflow-y: hidden;
}

.y-clip {
  overflow-y: clip;
}

.y-visible {
  overflow-y: visible;
}

.y-scroll {
  overflow-y: scroll;
}
```

<h4 id="pointer-events">Pointer events</h4>

```scss
.pointer-events-none {
  pointer-events: none;
}

.pointer-events-auto {
  pointer-events: auto;
}
```

<h4 id="position">Position</h4>

```scss
.static {
  position: static;
}

.fixed {
  position: fixed;
}

.absolute {
  position: absolute;
}

.relative {
  position: relative;
}

.sticky {
  position: sticky;
}
```

<h4 id="text-align">Text align</h4>

```scss
.text-left {
  text-align: left;
}

.text-center {
  text-align: center;
}

.text-right {
  text-align: right;
}

.text-justify {
  text-align: justify;
}

.text-start {
  text-align: start;
}

.text-end {
  text-align: end;
}
```

<h4 id="rotate">Rotate</h4>

```scss
.rotate-0 {
  transform: rotate(0deg);
}

.rotate-45 {
  transform: rotate(45deg);
}

.rotate-90 {
  transform: rotate(90deg);
}

.rotate-180 {
  transform: rotate(180deg);
}
```

<h4 id="z-index">Z index</h4>

```scss
@use '../config' as *;

.z-0 {
  z-index: $z_0;
}

.z-10 {
  z-index: $z_10;
}

.z-20 {
  z-index: $z_20;
}

.z-30 {
  z-index: $z_30;
}

.z-40 {
  z-index: $z_40;
}

.z-50 {
  z-index: $z_50;
}

.z-60 {
  z-index: $z_60;
}

.z-70 {
  z-index: $z_70;
}

.z-80 {
  z-index: $z_80;
}

.z-90 {
  z-index: $z_90;
}

.z-100 {
  z-index: $z_100;
}

.z-auto {
  z-index: $z_auto;
}
```

<br />

<img 
  src="./asset/illustration/divider.svg" 
  alt="divider" 
  width="100%" 
/>

<pre align="center">
  <a href="#top">BACK TO TOP</a>
</pre>

<img 
  src="./asset/illustration/divider.svg" 
  alt="divider" 
  width="100%" 
/>

<pre align="center">
  Copyright © All rights reserved,
  developed by LuisdaByte and
</pre>
<div align="center">
  <img src="./asset/illustration/astralys_logo.svg" width="120px" align="center" />
</div>

<img src="./asset/illustration/wave_footer.svg" width="100%" />