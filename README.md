# Zint

Modern, ready-to-use CSS gradients for text, built entirely with the OKLCH color
model.

[**Live Demo**](https://narkoz.github.io/zint/)

## Installation

Install the package from the npm registry:

```sh
npm install zint
```

## Usage

You can include the CSS in your project using multiple methods:

- **Import the compiled CSS directly** in your stylesheet or JavaScript file.
- **Use the Sass source** to customize or extend styles in your own Sass/SCSS files.
- **Load the CSS from a CDN** for quick integration without installing the package.

Choose the method that best fits your workflow and project needs.

### Compiled CSS

Import the compiled CSS in your main stylesheet or directly in your JavaScript/TypeScript entry file:

```css
@import "~zint/dist/zint.css";
```

or, with webpack/Vite/Parcel, directly in JS:

```js
import 'zint/dist/zint.css';
```

### Sass Source

If you want to customize variables or use mixins, import the main Sass file in your Sass/SCSS entry:

```scss
@use "zint/src/styles.scss";
```

### CDN

Link the stylesheet in your HTML:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/zint@1.0.0/dist/zint.min.css">
```

Then, apply the gradient classes to your text elements:

```html
<h1 class="zint-supernova-burst">Hello, World!</h1>
```

## Available Gradients

* `zint-aqua-flora`
* `zint-azure-tide`
* `zint-coral-glow`
* `zint-deep-sea-mist`
* `zint-dreamy-haze`
* `zint-forest-stream`
* `zint-fuchsia-flash`
* `zint-galactic-beam`
* `zint-glacial-ice`
* `zint-graphite-sheen`
* `zint-liquid-gold`
* `zint-meadow-spring`
* `zint-neon-fusion`
* `zint-pastel-morning`
* `zint-phoenix-fire`
* `zint-solar-flare`
* `zint-starlit-abyss`
* `zint-supernova-burst`
* `zint-tropical-zest`
* `zint-volcanic-sunset`

## License

Released under the BSD 2-clause license. See LICENSE.txt for details.
