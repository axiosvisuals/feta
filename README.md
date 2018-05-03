# feta
Feta is Axios' CSS styleguide. Sprinkle it on your project for maximum flavor.

## Variables

Variables cam be edited in `src/variables`

### Typography

```scss
// FONTS
$sans: "Gordita", Helvetica, Arial, sans-serif !default;
$serif: "Atiza", Georgia, serif !default;
$mono: "Liberation Mono", monospace !default;

// TYPOGRAPHY
$base-font-size: 16px !default;
$regular: 400 !default;

// SPACING
$space-05: .25rem !default; // 4px
$space-1: .5rem   !default; // 8px
$space-2:   1rem  !default; // 16px
$space-3: 1.5rem  !default; // 24px
$space-4:   2rem  !default; // 32px
$space-5:   3rem  !default; // 48px
$space-6: 4.5rem  !default; // 72px
```

### Colors

```scss
// Primary Colors
$color-axios-blue: #0a99e0;
$color-black: #222222;

// UI grays
$color-body-text: $color-gray-800;
$color-site-background: $color-gray-100;

// Axios Blue Tones
$color-axios-blue-100: #96d8ff;
$color-axios-blue-200: #73c8f7;
$color-axios-blue-300: #50b9f0;
$color-axios-blue-400: #2da9e8;
$color-axios-blue-500: #0a99e0;
$color-axios-blue-600: #087ebe;
$color-axios-blue-700: #05639b;
$color-axios-blue-800: #034879;
$color-axios-blue-900: #002d56;
$color-axios-blue-950: #051d2d;

// Tomato Tones
$color-tomato-100: #ffd1c6;
$color-tomato-200: #ffb3a0;
$color-tomato-300: #fb937a;
$color-tomato-400: #f97353;
$color-tomato-500: #e74e29;
$color-tomato-600: #d9421e;
$color-tomato-700: #ca330f;
$color-tomato-800: #ba2f0e;
$color-tomato-900: #b1290a;

// Orange Tones
$color-orange-100: #ffd7b2;
$color-orange-200: #ffd0a1;
$color-orange-300: #ffb87e;
$color-orange-400: #ff9b5a;
$color-orange-500: #ff7921;
$color-orange-600: #ff6602;
$color-orange-700: #f35d00;
$color-orange-800: #e15300;
$color-orange-900: #d44b00;

// Purple Tones
$color-purple-100: #d1cdff;
$color-purple-200: #b7b0ff;
$color-purple-300: #9686f7;
$color-purple-400: #7d61e1;
$color-purple-500: #6741d4;
$color-purple-600: #602fca;
$color-purple-700: #551bb7;
$color-purple-800: #4713a2;
$color-purple-900: #3d0e87;

// Khaki Tones
$color-khaki-100: #ebe2d7;
$color-khaki-200: #dbcfc1;
$color-khaki-300: #d3c3af;
$color-khaki-400: #c1af9a;
$color-khaki-500: #b09d86;
$color-khaki-600: #a8947b;
$color-khaki-700: #a18c72;
$color-khaki-800: #947f65;
$color-khaki-900: #846f55;

// Gray Tones
$color-gray-100: #f5f5f5;
$color-gray-200: #dcdcdc;
$color-gray-300: #c2c2c2;
$color-gray-400: #a9a9a9;
$color-gray-500: #979797;
$color-gray-600: #858585;
$color-gray-700: #696969;
$color-gray-800: #4a4a4a;
$color-gray-900: #222222;

// Green Tones
$color-green-100: #74ffb9;
$color-green-200: #46f5ad;
$color-green-300: #03e59f;
$color-green-400: #00d38f;
$color-green-500: #03c183;
$color-green-600: #00ac79;
$color-green-700: #009a68;
$color-green-800: #00865b;
$color-green-900: #01724c;
```

## Mixins

### prefix

Example:

```scss
p {@include prefix((transform: translate(-50%, -50%)), webkit ms);}
```
