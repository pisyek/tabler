---
title: Vue
description: Tabler Icons library for Vue framework.
summary: Tabler Icons for Vue offers a collection of customizable and scalable icons designed for use in Vue applications, providing a powerful tool for creating modern and engaging interfaces.
---

![](/img/icons/package-vue.png)


## Installation

{% include "docs/tabs-package.html" name="@tabler/icons-vue" %}

or just [download from Github](https://github.com/tabler/tabler-icons/releases).

## How to use

All icons are Vue components that contain SVG elements, so any icon can be imported and used as a component. It also helps to use treeshaking, so you only import the icons you use.

```vue
<template>
  <IconHome />
</template>

<script>
  // Returns Vue component
  import { IconHome } from '@tabler/icons-vue';

  export default {
    components: {
      IconHome
    }
  };
</script>
```

You can pass additional props to adjust the icon.

```html
<IconHome color="red" :size="48" stroke-width="1" />
```

### Props

| name          | type     | default      |
| ------------- | -------- | ------------ |
| `size`        | _Number_ | 24           |
| `color`       | _String_ | currentColor |
| `stroke`      | _Number_ | 2            |

