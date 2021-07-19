# CSS Descendant Selectors

Selects the `<a>` immediately under the `<section>` element, but not the ones within the `<p>` element that is a grand-child.

![](https://raw.githubusercontent.com/hoc-demos/images/main/css-descendants.png)
```css
section > a {
    color: green;
    text-decoration: none;
}
```

Selects the `<a>` elements within the `<li>` grand-child elements.

```css
ul a {
    color:deeppink;
    font-weight:800;
}

```
