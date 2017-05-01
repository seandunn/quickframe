# Quickframe

> Don't make the Demo look Done
> -- Kathy Sierra

Quickframe is a set of CSS styles to help make throw away wireframes
directly in HTML.

It aims to be as low ceremony as possible, with most of the styling
being provided by matching simple HTML tags.

Fonts are provided by Google Fonts CDN.  There is one file and no other dependencies.


## Tags and Classes
The main classes provided by quickframe are .grid and .wire.

```HTML
  <article class="grid Layout">
    <header class="wire Layout__header">header</header>
    <nav class="wire Layout__nav">nav</nav>
    <section class="wire Layout__section">
      <button>Do Something</button>
      <select>
        <option>1</option>
        <option>2</option>
        <option>3</option>
      </select>

      <input type="checkbox" id="test1" />
      <label htmlFor="test1">Red</label>
      <img alt="An image placeholder" />
    </section>
    <footer class="wire Layout__footer">footer</footer>
  </article>
```
