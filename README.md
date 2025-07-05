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
- Animation: transition-all

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
        className="block md:flex md:flex-col md:flex-auto md:justify-self-start w-full mx-auto p-3 text-xl text-center text-neutral-300  hover:text-lime-600  transition-all"
        rel="noopener noreferrer"
        target="_self"
        to="/"
      >
      </a>
    </li>
  </ul>
</nav>
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
  class="avalinginc-theme-heading-one my-3 text-3xl md:text-6xl subpixel-antialiased font-light text-left"
></h1>
```

## H3

```html
<h3
  class="avalinginc-theme-heading-three my-3 lg:my-6 text-xl lg:text-3xl subpixel-antialiased font-light text-left"
></h3>
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

## Button

```html
<button
  className="block w-full mx-auto p-3 text-center text-neutral-800 bg-lime-600 hover:text-neutral-900 hover:bg-neutral-300 transition-all cursor-pointer"
  type="submit"
>
  Sign Up
</button>
```

## Footer

```html
<footer>
  <ul class="avalinginc-theme-footer flex flex-col md:flex-row flex-auto my-3">
    <li class="flex items-center">
      <a
        class="mb-3 md:mb-0 md:mr-6 text-base antialiased font-black text-left transition-all"
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
  className="avalinginc-theme-copyright flex flex-col md:flex-row flex-auto my-3 text-xs subpixel-antialiased font-light text-left uppercase"
>
  <span>© {{ year }} Availing Inc. All rights reserved. </span>
  <span class="mx-3 invisible md:visible">|</span>
  <span>
    <a
      class="avalinginc-theme-policy transition-all text-xs subpixel-antialiased font-light text-left uppercase"
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
      class="avalinginc-theme-email transition-all text-xs subpixel-antialiased font-light text-left uppercase"
      rel="noopener noreferrer"
      target="_blank"
      href="mailto:contact@availing.io"
    >
      contact@availing.io
    </a></span
  >
</p>
```
