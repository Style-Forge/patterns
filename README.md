# style-forge.patterns

[![npm](https://img.shields.io/npm/v/style-forge.patterns)][npm-link]
[![npm](https://img.shields.io/npm/dm/style-forge.patterns)][npm-link]

Patterns CSS for [style-forge](https://www.npmjs.com/package/style-forge)

⚠️ The order in which elements are written within `pattern` is not important

<hr />

## Installation
```bash
npm install style-forge.patterns
```
```bash
yarn add style-forge.patterns
```

<hr />


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

## License [![NPM](https://img.shields.io/npm/l/style-forge.patterns)](https://github.com/Sarmaged/style-forge.patterns/blob/main/LICENSE)

Distributed under the MIT License. See `LICENSE` for more information.

[npm-link]: https://www.npmjs.com/package/style-forge.patterns
[github-link]: https://github.com/Sarmaged/style-forge.patterns
