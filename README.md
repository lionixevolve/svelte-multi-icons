# svelte-multi-icons

This package contains (for now) heroicons SVG inside a `.svelte` file for easy import (no need to do post-css stuff).

You can style this using *tailwindcss* just fine.

## Install

NPM
```bash
npm install --save-dev svelte-multi-icons
```

## Usage
* Use **Sd** prefix for Solid  Icons
* Use **"Md"** prefix for Outline Icons


```html
    <script>
        // Only import what you need!
        import { MdArrowUp, SmFilter } from 'svelte-multi-icons'
    </script>
    
    <MdArrowUp size="24" />
    <SmFilter size="1.5x" />
```

See all icons here: https://github.com/refactoringui/heroicons

## Author

The original package svelte-hero-icons is from Justin Voitel, big thanks!

This package is based on  [heroicons](https://github.com/refactoringui/heroicons) & [svelte-feather-icons](https://github.com/dylanblokhuis/svelte-feather-icons)
