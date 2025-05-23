---
title: Borders
summary: Use border utilities to quickly style the border and border-radius of an element. Great for images, buttons, or any other element.
description: Style elements with border utilities.
---

## Border direction

Borders can be applied to specific sides of an element using utility classes. This is particularly useful for styling individual sides of a box, such as highlighting the top border for emphasis or applying a separator between elements. Below are examples of how to set borders for each side of an element.

```html
<div class="border">1</div>
<div class="border-top">2</div>
<div class="border-end">3</div>
<div class="border-bottom">4</div>
<div class="border-start">5</div>
<div class="border-x">6</div>
<div class="border-y">7</div>
```

{% capture html -%}
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border"
>
  1
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-top"
>
  2
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-end"
>
  3
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-bottom"
>
  4
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-start"
>
  5
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-x"
>
  6
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-y"
>
  7
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}


## Border size

Border size utilities allow you to control the thickness of borders, providing flexibility to suit different design needs. You can add no border, a standard border, or a wide border for a more prominent effect. These classes are especially useful for creating visual hierarchy or highlighting specific elements.

```html
<div class="border-0">1</div>
<div class="border">2</div>
<div class="border-wide">3</div>
```

{% capture html -%}
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-0"
>
  1
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border"
>
  2
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border-wide"
>
  3
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Remove border

If you want to selectively remove borders from specific sides of an element, you can use border removal utilities. This feature simplifies styling tasks, such as creating a seamless connection between elements or achieving minimalistic designs.

```html
<div class="border border-top-0">1</div>
<div class="border border-end-0">2</div>
<div class="border border-bottom-0">3</div>
<div class="border border-start-0">4</div>
<div class="border border-x-0">5</div>
<div class="border border-y-0">6</div>
```

{% capture html -%}
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-top-0"
>
  1
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-end-0"
>
  2
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-bottom-0"
>
  3
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-start-0"
>
  4
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-x-0"
>
  5
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-y-0"
>
  6
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}


## Border color

Customizing the border color helps to enhance the visual appeal and consistency of your design. With utility classes, you can easily apply specific colors to borders, allowing for greater flexibility in creating visually distinct sections.

```html
<div class="border border-primary">1</div>
<div class="border border-secondary">2</div>
<div class="border border-success">3</div>
<div class="border border-warning">4</div>
<div class="border border-danger">5</div>
<div class="border border-info">6</div>
<div class="border border-dark">7</div>
<div class="border border-light">8</div>
```

{% capture html -%}
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-primary"
>
  1
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-secondary"
>
  2
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-success"
>
  3
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-warning"
>
  4
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-danger"
>
  5
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-info"
>
  6
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-dark"
>
  7
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-5 h-5 bg-light border border-light"
>
  8
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Border radius

Adding border radius gives elements smooth, rounded edges, which can make designs feel more modern and approachable. You can choose from various levels of rounding, including full circles, using the available utility classes.

```html
<div class="border rounded-0">1</div>
<div class="border rounded">2</div>
<div class="border rounded-1">3</div>
<div class="border rounded-2">4</div>
<div class="border rounded-3">5</div>
<div class="border rounded-circle">6</div>
```

{% capture html -%}
<div
  class="d-flex align-items-center justify-content-center text-secondary w-6 h-6 bg-light border rounded-0"
>
  1
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-6 h-6 bg-light border rounded"
>
  2
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-6 h-6 bg-light border rounded-1"
>
  3
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-6 h-6 bg-light border rounded-2"
>
  4
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-6 h-6 bg-light border rounded-3"
>
  5
</div>
<div
  class="d-flex align-items-center justify-content-center text-secondary w-6 h-6 bg-light border rounded-circle"
>
  6
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}


## Border opacity

You can adjust the opacity of borders to create subtle visual effects or to blend elements seamlessly into the background. By using border opacity utilities, you can control the transparency of borders, allowing for more creative and visually appealing designs. To change the opacity of a border, add the `border-opacity-*` class to the element.

```html
<div class="border border-success border-opacity-50">This is 50% opacity success border</div>
```

```html example 
<div class="border border-success p-2 mb-2">This is default success border</div>
<div class="border border-success p-2 mb-2 border-opacity-75">
  This is 75% opacity success border
</div>
<div class="border border-success p-2 mb-2 border-opacity-50">
  This is 50% opacity success border
</div>
<div class="border border-success p-2 mb-2 border-opacity-25">
  This is 25% opacity success border
</div>
<div class="border border-success p-2 border-opacity-10">This is 10% opacity success border</div>
```