# library

Availing Inc. — Feature-rich component library.

# Ordering of Tailwind CSS classes is important for consistency and readability.

- Availing Inc. Theme Class: avalinginc-theme-container
- Z-Index: z-0
- Position: relative
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
- Font Weight: font-light
- Font Style: not-italic
- Font Color: text-neutral-900
- Text Align: text-left
- Font Smoothing: subpixel-antialiased
- Hover: hover:text-neutral-600
- Animation: transition-all
- Cursor: cursor-pointer

## Container

```html
<div
  class="avalinginc-theme-container flex flex-col flex-auto justify-center items-center h-full w-auto max-w-3xl mt-[3vh] lg:mt-[9vh] mx-3 md:mx-9 xl:mx-auto"
></div>
```

## Column

```html
<div
  class="avalinginc-theme-column flex flex-col flex-auto justify-self-center"
></div>
```

## Navbar

```html
<nav className="block relative mb-[9vh] invisible hidden md:visible md:block">
  <ul className="flex flex-row items-center self-center mx-auto space-x-3">
    <li className="flex flex-col justify-self-start mr-9">
      <a rel="noopener noreferrer" target="_self" to="/">
        <img
          src="{Availinginc}"
          className="logo"
          alt="Availing Inc. logo"
          height="{30}"
          width="{30}"
        />
      </a>
    </li>
    <li>
      <a
        className="block md:flex md:flex-col md:flex-auto md:justify-self-start w-full mx-auto p-3 text-xl text-center text-neutral-300 hover:text-neutral-900 transition-all"
        rel="noopener noreferrer"
        target="_self"
        to="/"
      >
        Home
      </a>
    </li>
  </ul>
</nav>
```

## Logo

```html
<div
  class="avalinginc-theme-logo h-9 w-9 md:w-18 md:h-18 lg:w-30 lg:h-30 my-3"
></div>
```

## H1

```html
<h1
  class="avalinginc-theme-heading-one mx-auto text-3xl md:text-6xl font-bold text-neutral-900 text-left subpixel-antialiased"
></h1>
```

## H1

```html
<h1
  class="avalinginc-theme-heading-two my-3 lg:my-6 text-2xl lg:text-3xl font-bold text-neutral-900 text-left subpixel-antialiased"
></h1>
```

## H3

```html
<h3
  class="avalinginc-theme-heading-three my-3 lg:my-6 text-xl lg:text-3xl font-light text-neutral-900 text-left subpixel-antialiased"
></h3>
```

## Introduction

```html
<p
  className="avalinginc-theme-introduction my-3 text-xl md:text-3xl font-light text-neutral-900 text-left subpixel-antialiased"
></p>
```

## Paragraph

```html
<p
  className="avalinginc-theme-paragraph my-3 text-base font-light text-neutral-900 text-left subpixel-antialiased"
></p>
```

## Button

```html
<button
  className="block w-full mx-auto p-3 font-black text-neutral-800 bg-neutral-300 hover:text-neutral-900 hover:bg-neutral-400 text-center subpixel-antialiased transition-all cursor-pointer"
  type="submit"
>
  Sign Up
</button>
```

## Footer

```html
<footer>
  <ul
    class="avalinginc-theme-footer flex flex-col md:flex-row flex-auto my-3 font-black text-neutral-900 text-left subpixel-antialiased transition-all"
  >
    <li class="flex items-center">
      <a
        class="mb-3 md:mb-0 md:mr-6"
        rel="noopener noreferrer"
        target="_blank"
        href="https://x.com/availinginc/"
      >
        @availinginc
      </a>
    </li>
  </ul>
</footer>
```

## Copyright

```html
<p
  className="avalinginc-theme-copyright flex flex-col md:flex-row flex-auto my-3 text-xs font-light text-neutral-900 hover:text-neutral-600 text-left uppercase subpixel-antialiased transition-all"
>
  <span>© {{ year }} Availing Inc. All rights reserved. </span>
  <span class="mx-3 invisible md:visible">|</span>
  <span>
    <a
      class="avalinginc-theme-policy"
      rel="noopener noreferrer"
      target="_self"
      href="/privacy"
    >
      Privacy policy
    </a></span
  >
  <span class="mx-3 invisible md:visible">|</span>
  <span>
    <a
      class="avalinginc-theme-email"
      rel="noopener noreferrer"
      target="_blank"
      href="mailto:contact@availing.io"
    >
      contact@availing.io
    </a></span
  >
</p>
```
