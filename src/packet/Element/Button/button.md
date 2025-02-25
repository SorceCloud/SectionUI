# Button component

<br />

Button component with multiple styles, colors and sizes.

## Basic usage

```ts
import btn from "sectionui"
```
## Basic
<div class="flex flex-wrap items-center gap-3">
  <btn>Primary</btn>
  <btn loading>Loading</btn>
  <btn disabled>Disabled</btn>
  <btn pills>Primary pills</btn>
  <btn variant="outline">Outline</btn>
  <btn variant="link">Link</btn>
</div>

```ts
  <btn>Primary</btn>
  <btn loading>Loading</btn>
  <btn disabled>Disabled</btn>
  <btn pills>Primary pills</btn>
  <btn variant="outline">Outline</btn>
  <btn variant="link">Link</btn>
```
## Colors

<div class="flex flex-wrap items-center gap-3">
  <btn color="primary">Primary </btn>
  <btn color="secondary">Secondary </btn>
  <btn color="success">Success </btn>
  <btn color="error">Error </btn>
  <btn color="warning">Warning </btn>
</div>

```ts
  <btn>Primary</btn>
  <btn loading>Loading</btn>
  <btn disabled>Disabled</btn>
  <btn pills>Primary pills</btn>
  <btn variant="outline">Outline</btn>
  <btn variant="link">Link</btn>
```
## Outline

<div class="flex flex-wrap items-center gap-3">
  <btn color="primary" variant="outline">Primary </btn>
  <btn color="secondary" variant="outline">Secondary </btn>
  <btn color="success" variant="outline">Success </btn>
  <btn color="error" variant="outline">
   </btn>
  <btn color="warning" variant="outline">Warning </btn>
</div>

```ts
  <btn color="primary" variant="outline">Primary </btn>
  <btn color="secondary" variant="outline">Secondary </btn>
  <btn color="success" variant="outline">Success </btn>
  <btn color="error" variant="outline">Error </btn>
  <btn color="warning" variant="outline">Warning </btn>
```
## Transparent

<div class="flex flex-wrap items-center gap-3">
  <btn color="primary" variant="transparent">Primary </btn>
  <btn color="secondary" variant="transparent">Secondary </btn>
  <btn color="success" variant="transparent">Success </btn>
  <btn color="error" variant="transparent">Error </btn>
  <btn color="warning" variant="transparent">Warning </btn>
</div>

```ts
  <btn color="primary" variant="transparent">Primary </btn>
  <btn color="secondary" variant="transparent">Secondary </btn>
  <btn color="success" variant="transparent">Success </btn>
  <btn color="error" variant="transparent">Error </btn>
  <btn color="warning" variant="transparent">Warning </btn>
```
## Pills

<div class="flex flex-wrap items-center gap-3">
  <btn color="primary" pills>Primary </btn>
  <btn color="secondary" pills>Secondary </btn>
  <btn color="success" pills>Success </btn>
  <btn color="error" pills>Error </btn>
  <btn color="warning" pills>Warning </btn>
</div>

```ts
  <btn color="primary" pills>Primary </btn>
  <btn color="secondary" pills>Secondary </btn>
  <btn color="success" pills>Success </btn>
  <btn color="error" pills>Error </btn>
  <btn color="warning" pills>Warning </btn>
```
## Sizes

<div class="flex flex-wrap items-center gap-3">
  <btn size="xs">Extra-small </btn>
  <btn size="sm">Small </btn>
  <btn>normal </btn>
  <btn size="lg">Large </btn>
  <btn size="xl">Extra-large </btn>
</div>

```ts
  <btn size="xs">Extra-small </btn>
  <btn size="sm">Small </btn>
  <btn>normal </btn>
  <btn size="lg">Large </btn>
  <btn size="xl">Extra-large </btn>
```
## Responsive 

<div class="flex flex-wrap items-center gap-3">
  <btn size="sm" md="lg">Default(sm) md(lg)</btn>
  <btn size="lg" md="xs">Default(lg) md(xs)</btn>
</div>

```ts
  <btn size="sm" md="lg">Default(sm) md(lg)</btn>
  <btn size="lg" md="xs">Default(lg) md(xs)</btn>
```



## Link

<div class="flex flex-wrap items-center gap-3">
  <btn color="primary" variant="link">Primary </btn>
  <btn color="secondary" variant="link">Secondary </btn>
  <btn color="success" variant="link">Success </btn>
  <btn color="error" variant="link">Error </btn>
  <btn color="warning" variant="link">Warning </btn>
</div>

```ts
  <btn color="primary" variant="link">Primary </btn>
  <btn color="secondary" variant="link">Secondary </btn>
  <btn color="success" variant="link">Success </btn>
  <btn color="error" variant="link">Error </btn>
  <btn color="warning" variant="link">Warning </btn>
```
## Circle

<div class="flex flex-wrap items-center gap-3">
  <btn circle>
    <icn name="bell" xl/>
  </btn>
  <btn circle variant="outline">
    <icn name="bell" xl/>
  </btn>
</div>

```ts
  <btn circle>
    <icn name="bell" xl/>
  </btn>
  <btn circle variant="outline">
    <icn name="bell" xl/>
  </btn>
```

## Tag 
<div class="flex flex-wrap items-center gap-3">
  <btn tag="a" href="/" variant="link" >Home </btn>
  <btn tag="RouterLink" to="/components/button">Secondary </btn>
</div>

```ts
  <btn tag="a" href="/" variant="link" >Home </btn>
  <btn tag="RouterLink" to="/components/button">Secondary </btn>
```

## API

| 表格 | 表格 | 表格 | 表格 |
| ---- | ---- | ---- | ---- |
| 表格 | 表格 | 表格 | 表格 |


