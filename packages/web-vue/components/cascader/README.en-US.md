```yaml
meta:
  type: Component
  category: Data Entry
title: Cascader
description: Refers to the use of multi-level classification to separate the options when the number of selector options is large.
```

*Auto translate by google.*

@import ./__demo__/basic.md

@import ./__demo__/clear.md

@import ./__demo__/disabled.md

@import ./__demo__/format.md

@import ./__demo__/multiple.md

@import ./__demo__/search.md

@import ./__demo__/path.md


### `<cascader>` Props

|Attribute|Description|Type|Default|
|---|---|---|:---:|
|path-mode|Whether the value is a path|`boolean`|`false`|
|multiple|Whether it is a multi-selection state|`boolean`|`false`|
|model-value **(v-model)**|Value|`string \| string[] \| undefined \| (string \| string[])[]`|`-`|
|default-value|Default value (uncontrolled state)|`string \| string[] \| undefined \| (string \| string[])[]`|`'' | undefined | []`|
|options|Options for cascader|`CascaderOption[]`|`[]`|
|disabled|Whether to disable|`boolean`|`false`|
|error|Whether it is an error state|`boolean`|`false`|
|allow-search|Whether to allow searching|`boolean`|`false`|
|allow-clear|Whether to allow clear|`boolean`|`false`|
|input-value **(v-model)**|The value of the input|`string`|`-`|
|default-input-value|The default value of the input (uncontrolled state)|`string`|`''`|
|popup-visible **(v-model)**|Whether to show the dropdown|`boolean`|`-`|
|expand-trigger|Expand the trigger method of the next level|`string`|`'click'`|
|default-popup-visible|Whether to display the dropdown by default (uncontrolled state)|`boolean`|`false`|
|placeholder|Placeholder|`string`|`-`|
|popup-container|Mount container for popup|`string \| HTMLElement \| null \| undefined`|`-`|
|format-label|Format display content|`(options: CascaderOptionInfo[]) => string`|`-`|
### `<cascader>` Events

|Event Name|Description|Parameters|
|---|---|---|
|change|Triggered when the selected value changes|value: `string \| string[] \| undefined \| (string \| string[])[]`|
|input-value-change|Triggered when the input value changes|value: `string`|
|clear|Triggered when the clear button is clicked|-|
|search|Triggered when the user searches|value: `string`|
|popup-visible-change|Triggered when the display state of the dropdown changes|visible: `boolean`|
|focus|Triggered when focus|-|
|blur|Triggered when blur|-|


