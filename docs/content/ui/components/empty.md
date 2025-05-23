---
title: Empty states
summary: Empty states or blank pages are commonly used as placeholders for first-use, empty data or error screens. Their aim is to engage users when there is no content to display and that is why their design is extremely important from the point of view of the user experience of your website or app.
description: Engage users in empty or error screens.
---

## Default markup

Use the default empty state to engage users in the critical moments of their experience with your website or app. A good empty state screen should let users know what is happening and what they should do next as well as encourage them to take action.

{% capture html -%}
<div class="empty">
  <div class="empty-icon">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="icon"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      stroke-width="2"
      stroke="currentColor"
      fill="none"
      stroke-linecap="round"
      stroke-linejoin="round"
    >
      <path stroke="none" d="M0 0h24v24H0z" fill="none" />
      <circle cx="12" cy="12" r="9" />
      <line x1="9" y1="10" x2="9.01" y2="10" />
      <line x1="15" y1="10" x2="15.01" y2="10" />
      <path d="M9.5 15.25a3.5 3.5 0 0 1 5 0" />
    </svg>
  </div>
  <p class="empty-title">No results found</p>
  <p class="empty-subtitle text-secondary">
    Try adjusting your search or filter to find what you're looking for.
  </p>
  <div class="empty-action">
    <a href="#" class="btn btn-primary">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <circle cx="10" cy="10" r="7" />
        <line x1="21" y1="21" x2="15" y2="15" />
      </svg>
      Search again
    </a>
  </div>
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Empty state with illustration

Make your empty state screen more attractive and engaging by adding an illustration. Thanks to a more personalized design, you will improve your brand image and make your website or app more user friendly.

{% capture html -%}
<div class="empty">
  <div class="empty-img">
    <img src="..." height="128" alt="" />
  </div>
  <p class="empty-title">Invoices are managed from here</p>
  <p class="empty-subtitle text-secondary">
    Try adjusting your search or filter to find what you're looking for.
  </p>
  <div class="empty-action">
    <a href="#" class="btn btn-primary">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <line x1="12" y1="5" x2="12" y2="19" />
        <line x1="5" y1="12" x2="19" y2="12" />
      </svg>
      New invoice
    </a>
  </div>
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Empty state with header

Instead of adding an icon or illustration you can simply give the text:

{% capture html -%}
<div class="empty">
  <div class="empty-header">404</div>
  <p class="empty-title">Oops… You just found an error page</p>
  <p class="empty-subtitle text-secondary">
    Try adjusting your search or filter to find what you're looking for.
  </p>
  <div class="empty-action">
    <a href="#" class="btn btn-primary">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <line x1="5" y1="12" x2="19" y2="12" />
        <line x1="5" y1="12" x2="11" y2="18" />
        <line x1="5" y1="12" x2="11" y2="6" />
      </svg>
      Take me home
    </a>
  </div>
</div>
{%- endcapture %}
{% include "docs/example.html" html=html %}

```html
<div class="empty">
  <div class="empty-header">404</div>
  <p class="empty-title">Oops… You just found an error page</p>
  <p class="empty-subtitle text-secondary">
    Try adjusting your search or filter to find what you're looking for.
  </p>
  <div class="empty-action">
    <a href="#" class="btn btn-primary">
      {% include "ui/icon.html" icon="arrow-left" %}
      Take me home
    </a>
  </div>
</div>
```
