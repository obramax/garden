---
title: Typography
layout: page.jade
sidebar: true
collection: css
path: typography
---

# Typography
All typography tags/classes uses `rem` in order to set size. The `$default-font-size` variable uses `16px`.

In case you use Garden css components individually (bundling with PostCSS), you can provide your own `$default-font-size` to change it.
We provide both markup tags and classes in order to handle text styling with flexibility.

## Headings

In alternative to using directly `<h[1-6]>`, you can use `.heading-[1-6]` classes for the same style of a heading tag.

<div class="example">
  <h1>Heading 1</h1>

  <hr />

  <h2>Heading 2</h2>

  <hr />

  <h3>Heading 3</h3>

  <hr />

  <h4>Heading 4</h4>

  <hr />

  <h5>Heading 5</h5>

  <hr />

  <h6>Heading 6</h6>
</div>

```html
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
```

## Paragraphs

Tag `<p>` is styled by default. You can also use the `.paragraph` class.

<div class="example">
  <p>Paragraph tag</p>

  <hr />

  <div class="paragraph">Paragraph class</div>
</div>

```html
  <p>Paragraph tag</p>
  <div class="paragraph">Paragraph class</div>
```

## Inline text

Tags such as `<strong>`, `<b>`, `<em>`, `<i>`, `<u>` are by default stylized. You can also use `.strong` and `.italic`, `.underlined` to mimic their styles.

<div class="example">
  <strong>strong text</strong> <br>
  <b>also strong text</b> <br>
  <div class="strong">also also strong</div>

  <hr />

  <em>italic text</em> <br>
  <i>also italic text</i> <br>
  <div class="italic">also also italic</div>

  <hr />

  <u>underlined text</u> <br>
  <div class="underlined">also underlined</div>
</div>

```html
  <strong>strong text</strong>
  <b>also strong text</b>
  <div class="strong">also also strong</div>

  <em>italic text</em>
  <i>also italic text</i>
  <div class="italic">also also italic</div>

  <u>underlined text</u>
  <div class="underlined">also underlined</div>
```

## Text transformation

<div class="example">
  <p class="capitalize">capitalized text</p>

  <p class="uppercase">uppercase text</p>

  <p class="lowercase">LOWERCASE TEXT</p>
</div>

```html
  <p class="capitalize">capitalized text</p>
  <p class="uppercase">uppercase text</p>
  <p class="lowercase">LOWERCASE TEXT</p>
```

## Text alignment

<div class="example">
  <p class="align-left">Left alignment</p>

  <p class="align-right">Right alignment</p>

  <p class="align-center">Center alignment</p>

  <p class="align-justify">Justified text</p>

  <p class="align-nowrap">No wrap</p>
</div>

```html
  <p class="align-left">Left alignment</p>
  <p class="align-right">Right alignment</p>
  <p class="align-center">Center alignment</p>
  <p class="align-justify">Justified</p>
  <p class="align-nowrap">No wrap</p>
```