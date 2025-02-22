# uchu-tailwind

[Uchu](https://uchu.style) for tailwind.

Thanks https://github.com/NeverCease/uchu.

## Usage

1. Install `uchu-tailwind` via npm using Bun, Deno, pnpm, yarn or npm.
2. Change your tailwind entry css.
```diff
  @import "tailwindcss";
+ @import "uchu-tailwind" layer(theme);
```

## Example

```html
<div class="text-uchu-red">Hello</div>
<div class="text-uchu-purple-5">World</div>
```
