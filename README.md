# library

Availing Inc. — Feature-rich component library.

# Ordering of Tailwind CSS classes is important for consistency and readability.

- Avaling Inc. Theme Class: avalinginc-theme-container
- Scale: sm: md: lg: xl: 3xl:
- Display: block / flex
- Flex Direction: flex-col
- Flex Grow: flex-auto
- Flex Item Alignment: items-center
- Height: h-9
- Max Height: max-h-3xl
- Width: w-9
- Max Width: max-w-3xl
- Margin Top: mt-9
- Margin X Number: mx-9
- Margin X Auto: mx-auto
- Margin Y Number: my-9
- Margin Y Auto: my-auto
- Font Family: font-sans
- Font Size: text-3xl
- Font Smoothing: subpixel-antialiased
- Font Style: not-italic
- Font Weight: font-light
- Text Align: text-left

## Container

```html
<div
  class="avalinginc-theme-container block h-full w-auto max-w-6xl mx-3 md:mx-9 xl:mx-auto"
></div>
```

## Column

```html
<div class="avalinginc-theme-column flex flex-col flex-auto"></div>
```

## Logo

```html
<div
  class="avalinginc-theme-logo w-9 h-9 md:w-18 md:h-18 lg:w-30 lg:h-30 my-3"
></div>
```

## H1

```html
<h1
  class="avalinginc-theme-heading-one my-3 text-3xl md:text-6xl subpixel-antialiased font-black text-left"
></h1>
```

## H3

```html
<h1
  class="avalinginc-theme-heading-three my-3 lg:my-6 text-xl lg:text-3xl subpixel-antialiased font-light text-left"
></h1>
```

## Introduction

```html
<p
  className="avalinginc-theme-introduction my-3 text-xl md:text-3xl subpixel-antialiased font-light text-left"
></p>
```

## Paragraph

```html
<p
  className="avalinginc-theme-paragraph my-3 text-base subpixel-antialiased font-light text-left"
></p>
```

## Footer

```html
<footer>
  <ul class="avalinginc-theme-footer flex flex-col md:flex-row flex-auto my-3">
    <li class="flex items-center">
      <a
        class="transition-all"
        rel="noopener noreferrer"
        target="_blank"
        href="https://x.com/availinginc/"
      >
        <p class="mr-9 text-base subpixel-antialiased font-black text-left"></p>
      </a>
    </li>
  </ul>
</footer>
```

## Copyright

```html
<p
  className="avalinginc-theme-copyright my-3 text-xs subpixel-antialiased font-light text-left"
></p>
```
