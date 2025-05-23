---
title: Tooltips
summary: Tooltips are text labels which appear when a user hovers over an interface element. They explain the interface elements that may be unclear for users and guide them when they need help. If used properly, tooltips can significantly enhance user experience and add value to your website or software.
bootstrapLink: components/tooltips/
description: Guide users with informative tooltips.
---

## Default markup

Use the default markup to create tooltips that will help users understand particular elements of your interface. You can decide where the text label is to be displayed - at the top, bottom or on either side of the element.

{% capture html -%}
<button
  type="button"
  class="btn"
  data-bs-toggle="tooltip"
  data-bs-placement="top"
  title="Tooltip on top"
>
  Tooltip on top
</button>
<button
  type="button"
  class="btn"
  data-bs-toggle="tooltip"
  data-bs-placement="right"
  title="Tooltip on right"
>
  Tooltip on right
</button>
<button
  type="button"
  class="btn"
  data-bs-toggle="tooltip"
  data-bs-placement="bottom"
  title="Tooltip on bottom"
>
  Tooltip on bottom
</button>
<button
  type="button"
  class="btn"
  data-bs-toggle="tooltip"
  data-bs-placement="left"
  title="Tooltip on left"
>
  Tooltip on left
</button>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Tooltip with HTML

If the default tooltip is not enough, you can add the option to use HTML code in the text to highlight particular bits of information and make the content more attractive.

{% capture html -%}
<button
  type="button"
  class="btn"
  data-bs-toggle="tooltip"
  data-bs-html="true"
  title="<em>Tooltip</em> <u>with</u> <b>HTML</b>"
>
  Tooltip with HTML
</button>
{%- endcapture %}
{% include "docs/example.html" html=html %}
