---
layout: page.11ty.cjs
title: <orion-menu> ⌲ Home
---

# &lt;orion-menu>

`<orion-menu>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<orion-menu>` is just an HTML element. You can it anywhere you can use HTML!

```html
<orion-menu></orion-menu>
```

  </div>
  <div>

<orion-menu></orion-menu>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<orion-menu>` can be configured with attributed in plain HTML.

```html
<orion-menu name="HTML"></orion-menu>
```

  </div>
  <div>

<orion-menu name="HTML"></orion-menu>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<orion-menu>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;orion-menu&gt;</h2>
    <orion-menu .name=${name}></orion-menu>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;orion-menu&gt;</h2>
<orion-menu name="lit-html"></orion-menu>

  </div>
</section>
