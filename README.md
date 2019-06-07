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

See `feta/src/variables/_colors`

## Mixins

### prefix

Example:

```scss
p {@include prefix((transform: translate(-50%, -50%)), webkit ms);}
```
