```yaml
title:
  zh-CN: 显示箭头元素
  en-US: Show Arrow
```

## zh-CN

通过`show-arrow`属性，可以展示默认的箭头元素。也可以通过`arrow-class`或`arrow-style`进行定制。

---

## en-US

---

```vue
<template>
  <a-space>
    <a-trigger class="demo-arrow" trigger="click">
      <a-button>Click Me</a-button>
      <template #content>
        <a-empty />
      </template>
    </a-trigger>
    <a-trigger class="demo-arrow" trigger="click" show-arrow>
      <a-button>Click Me (Arrow)</a-button>
      <template #content>
        <a-empty />
      </template>
    </a-trigger>
  </a-space>
</template>

<style lang="less">
.demo-arrow {
  border-radius: 4px;
  box-shadow: 0 2px 8px 0 rgba(0, 0, 0, 0.15);

  &-popup-content {
    padding: 10px;
    width: 200px;
    background-color: var(--color-bg-popup);
    border-radius: 4px;
  }

  &-popup-arrow {
    box-shadow: 0 2px 8px 0 rgba(0, 0, 0, 0.15);
  }
}
</style>
```
