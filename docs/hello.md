---
sidebar_label: 'Hellloooo'
sidebar_position: 1
---

# This is first heading

---
id: my-doc-id
title: My document title
description: My document description
slug: /my-custom-url
---

## Markdown heading

Markdown text with [links](./hello.md)

# Hello

Welcome to this page.....

Let's see how to [Create a page](/create-a-page).

![Docusaurus logo](/img/docusaurus.png)


```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
  return <h1>Hello, Docusaurus!</h1>;
}
```

:::tip[My tip]

Use this awesome feature option

:::

:::danger[Take care]

This action is dangerous

:::


export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Sky blue</Highlight> !