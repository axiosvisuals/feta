# feta
Feta is Axios' CSS styleguide. Sprinkle it on your project for maximum flavor.

## Variables

```scss
// FONTS
$sans: "Gordita", Helvetica, Arial, sans-serif !default;
$serif: "Atiza", Georgia, serif !default;
$mono: "Liberation Mono", monospace !default;

// COLORS
$grey-darkest:       #222222 !default;
$grey-darker:        #4A4A4A !default;
$grey-dark:          #848484 !default;
$grey:               #c2c2c2 !default;
$grey-light:         #dcdcdc !default;
$grey-lighter:       #F0F0F0 !default;
$grey-lightest:      #F9F9F9 !default;
$blue:               #008dc8 !default;
$blue-secondary:     #175B87 !default;
$navy:               #01356E !default;
$navy-secondary:     #175B87 !default;
$red:                #E74E2A !default;
$red-secondary:      #AB361A !default;
$orange:             #FF6602 !default;
$orange-secondary:   #CA5508 !default;
$khaki:              #B09D86 !default;
$khaki-secondary:    #7F684E !default;
$purple:             #5827AE !default;
$purple-secondary:   #310F6B !default;

// TYPOGRAPHY
$base-font-size: 16px !default;
$regular: 400 !default;
$bold: 600    !default;


// SPACING
$space-05: .25rem !default; // 4px
$space-1: .5rem   !default; // 8px
$space-2:   1rem  !default; // 16px
$space-3: 1.5rem  !default; // 24px
$space-4:   2rem  !default; // 32px
$space-5:   3rem  !default; // 48px
$space-6: 4.5rem  !default; // 72px
```

## Mixins

### prefix

Example:

```scss
p {@include prefix((transform: translate(-50%, -50%)), webkit ms);}
```
