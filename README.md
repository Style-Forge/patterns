
# Style-Forge.Patterns

![npm](https://img.shields.io/npm/v/style-forge.patterns)
![npm](https://img.shields.io/npm/dm/style-forge.patterns)
![license](https://img.shields.io/npm/l/style-forge.patterns)
![build](https://github.com/Sarmaged/style-forge.patterns/actions/workflows/publish.yml/badge.svg)

## Description

`Style-Forge.Patterns` is a versatile and efficient CSS utility library designed to simplify the creation and management of CSS patterns and utilities. It offers a comprehensive collection of pre-defined CSS classes, enabling developers to rapidly build responsive and consistent user interfaces without the need for writing repetitive styles from scratch.

## Installation

You can install the package via npm or yarn:

```bash
npm install style-forge.patterns
```

```bash
yarn add style-forge.patterns
```

## Usage

After installation, you can import the CSS file into your project:

```css
@import "style-forge.patterns";
```

Or, if you are using Webpack or another module bundler:

```js
import 'style-forge.patterns';
```

## Site model

<u>Grid model for the site [media query for mobile devices]</u>

```html
<div class="sf-pattern area-header area-footer area-menu area-aside">
  <div class="area-footer">Footer</div>
  <div class="area-header">Header</div>
  <div class="area-menu">Menu</div>
  <div class="area-aside">Aside</div>

  <!-- Should always be -->
  <div class="area-main">
    <h1>Main</h1>
  </div>
  <!-- // -->
</div>
```

### Options

<details>
  <summary><strong><code>pattern</code> - This is the main Grid block</strong></summary>

  ```html
  <div class="sf-pattern">
    <div class="area-main">
      <h1>Main</h1>
    </div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>header</code></strong></summary>

  ```html
  <div class="sf-pattern area-header">
    <div class="area-main">
      <h1>Main</h1>
    </div>
    <div class="area-header">Header</div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>footer</code></strong></summary>

  ```html
  <div class="sf-pattern area-footer">
    <div class="area-main">
      <h1>Main</h1>
    </div>
    <div class="area-footer">Footer</div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>menu</code></strong></summary>

  ```html
  <div class="sf-pattern area-menu">
    <div class="area-main">
      <h1>Main</h1>
    </div>
    <div class="area-menu">Menu</div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>aside</code></strong></summary>

  ```html
  <div class="sf-pattern area-aside">
    <div class="area-main">
      <h1>Main</h1>
    </div>
    <div class="area-aside">Aside</div>
  </div>
  ```
</details>

## Media model

Grid model for the media

```html
<article class="sf-pattern area-media">
  <figure>
    <img src="https://via.placeholder.com/128x128" alt="" />
  </figure>
  <section class="area-main">
    <p>
      Our psychic everything for grace is to witness others safely.
    </p>
  </section>
</article>
```

<details>
  <summary><strong><code>Inheritance example</code></strong></summary>

```html
<article class="sf-pattern area-media">
  <figure>
    <img src="https://via.placeholder.com/128x128" alt="" />
  </figure>
  <section class="area-main">
    <p>
      Our psychic everything for grace is to witness others safely.
    </p>
    <p>
      Our psychic everything for grace is to witness others safely.
    </p>
    <article class="sf-pattern area-media">
      <figure>
        <img src="https://via.placeholder.com/128x128" alt="" />
      </figure>
      <section class="area-main">
        <p>
          Our psychic everything for grace is to witness others safely.
        </p>
      </section>
    </article>
  </section>
</article>
```
</details>

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

- [style-forge](https://github.com/Sarmaged/style-forge)
- [style-forge.base](https://github.com/Sarmaged/style-forge.base)
- [style-forge.colors](https://github.com/Sarmaged/style-forge.colors)
- [style-forge.form](https://github.com/Sarmaged/style-forge.form)
- [style-forge.helpers](https://github.com/Sarmaged/style-forge.helpers)
- [style-forge.patterns](https://github.com/Sarmaged/style-forge.patterns)
- [style-forge.themes](https://github.com/Sarmaged/style-forge.themes)

## Authors

- **Dmitrii Sagalov** - *Expert in interface development* - [Sarmaged](https://github.com/Sarmaged)

## Contact

If you have any questions or suggestions, please open an issue in [Issues](https://github.com/Sarmaged/style-forge.patterns/issues).
