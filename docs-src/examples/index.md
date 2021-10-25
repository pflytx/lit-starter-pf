---
layout: example.11ty.cjs
title: <greet-counter> ⌲ Examples ⌲ Basic
tags: example
name: Basic
description: A basic example
---

<style>
  greet-counter p {
    border: solid 1px blue;
    padding: 8px;
  }
</style>
<greet-counter>
  <p>This is child content</p>
</greet-counter>

<h3>CSS</h3>

```css
p {
  border: solid 1px blue;
  padding: 8px;
}
```

<h3>HTML</h3>

```html
<greet-counter>
  <p>This is child content</p>
</greet-counter>
```
