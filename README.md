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
  class="avalinginc-theme-container z-0 flex flex-col flex-auto justify-center items-center h-full w-auto max-w-6xl my-[3vh] mx-3 xl:mx-auto"
></div>
```

## Column

```html
<div
  class="avalinginc-theme-column flex flex-col flex-auto justify-self-center h-auto min-w-0 m-3 p-3"
></div>
```

## Navbar

```html
<nav className="relative my-[9vh] invisible md:visible hidden md:block">
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
        href="/"
      >
        Home
      </a>
    </li>
  </ul>
</nav>
<nav
  className="z-30 relative block md:hidden visible md:invisible my-[9vh] md:my-0"
>
  <ul className="flex flex-row justify-center items-center self-center">
    <li className="flex flex-col flex-auto justify-self-start">
      <a rel="noopener noreferrer" target="_self" href="/"> Home </a>
    </li>
  </ul>
</nav>
```

## Logo

```html
<div
  class="avalinginc-theme-logo h-9 w-9 max-h-9 max-w-9 md:h-18 md:w-18 md:max-h-18 md:max-w-18 my-3"
></div>
```

## H1

```html
<h1
  class="avalinginc-theme-heading-one mx-auto text-5xl md:text-6xl font-bold text-neutral-900 text-left subpixel-antialiased"
></h1>
```

## H2

```html
<h1
  class="avalinginc-theme-heading-two my-3 lg:my-6 text-4xl lg:text-5xl font-bold text-neutral-900 text-left subpixel-antialiased"
></h1>
```

## H3

```html
<h3
  class="avalinginc-theme-heading-three my-3 lg:my-6 text-3xl lg:text-4xl font-light text-neutral-900 text-left subpixel-antialiased"
></h3>
```

## Introduction

```html
<p
  className="avalinginc-theme-introduction my-3 text-2xl md:text-3xl font-light text-neutral-900 text-left subpixel-antialiased"
></p>
```

## Paragraph

```html
<p
  className="avalinginc-theme-paragraph my-3 text-base md:text-xl font-light text-neutral-900 text-left subpixel-antialiased"
></p>
```

```html
<p
  className="avalinginc-theme-paragraph my-3 text-base md:text-2xl font-light text-neutral-900 text-left subpixel-antialiased"
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
    class="avalinginc-theme-footer flex flex-col md:flex-row flex-auto my-3 font-black text-neutral-900 text-left subpixel-antialiased"
  >
    <li class="flex items-center">
      <a
        class="mb-3 md:mb-0 md:mr-6 hover:text-neutral-300 transition-all"
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
  className="avalinginc-theme-copyright flex flex-col md:flex-row flex-auto my-[3vh] text-xs font-light text-neutral-900 hover:text-neutral-600 text-left uppercase subpixel-antialiased transition-all"
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
