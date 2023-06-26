# style-forge.patterns

[![npm](https://img.shields.io/npm/v/style-forge.patterns)][npm-link]
[![npm](https://img.shields.io/npm/dm/style-forge.patterns)][npm-link]

Patterns CSS for [style-forge](https://www.npmjs.com/package/style-forge)

⚠️ The order in which elements are written within `pattern` is not important

<hr />

## Site model

<u>Grid model for the site [media query for mobile devices]</u>

```html
<div pattern header footer menu aside>
  <div footer>Footer</div>
  <div header>Header</div>
  <div menu>Menu</div>
  <div aside>Aside</div>

  <!-- Всегда должен быть -->
  <div main>
    <h1>Main</h1>
  </div>
  <!-- // -->
</div>
```

### Options

<details>
  <summary><strong><code>pattern</code> - Это главный Grid блок</strong></summary>

  ```html
  <div pattern>
    <div main>
      <h1>Main</h1>
    </div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>header</code></strong></summary>

  ```html
  <div pattern header>
    <div main>
      <h1>Main</h1>
    </div>
    <div header>Header</div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>footer</code></strong></summary>

  ```html
  <div pattern footer>
    <div main>
      <h1>Main</h1>
    </div>
    <div footer>Footer</div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>menu</code></strong></summary>

  ```html
  <div pattern menu>
    <div main>
      <h1>Main</h1>
    </div>
    <div menu>Menu</div>
  </div>
  ```
</details>

<details>
  <summary><strong><code>aside</code></strong></summary>

  ```html
  <div pattern aside>
    <div main>
      <h1>Main</h1>
    </div>
    <div aside>Aside</div>
  </div>
  ```
</details>

## Media model

Grid model for the media

```html
<article pattern media>
  <figure>
    <img src="https://via.placeholder.com/128x128" alt="" />
  </figure>
  <section main>
    <p>
      Our psychic everything for grace is to witness others safely.
    </p>
  </section>
</article>
```

<details>
  <summary><strong><code>Inheritance example</code></strong></summary>

```html
<article pattern media>
  <figure>
    <img src="https://via.placeholder.com/128x128" alt="" />
  </figure>
  <section main>
    <p>
      Our psychic everything for grace is to witness others safely.
    </p>
    <p>
      Our psychic everything for grace is to witness others safely.
    </p>
    <article pattern media>
      <figure>
        <img src="https://via.placeholder.com/128x128" alt="" />
      </figure>
      <section main>
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
