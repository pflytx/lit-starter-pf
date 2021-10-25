---
layout: page.11ty.cjs
title: <greet-counter> ⌲ Home
---

# &lt;greet-counter>

`<greet-counter>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<greet-counter>` is just an HTML element. You can it anywhere you can use HTML!

```html
<greet-counter></greet-counter>
```

  </div>
  <div>

<greet-counter></greet-counter>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<greet-counter>` can be configured with attributed in plain HTML.

```html
<greet-counter name="HTML"></greet-counter>
```

  </div>
  <div>

<greet-counter name="HTML"></greet-counter>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<greet-counter>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;greet-counter&gt;</h2>
    <greet-counter .name=${name}></greet-counter>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;greet-counter&gt;</h2>
<greet-counter name="lit-html"></greet-counter>

  </div>
</section>
