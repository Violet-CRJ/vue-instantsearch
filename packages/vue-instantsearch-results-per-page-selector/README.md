Vue Algolia Results Per Page Selector
---

A component that lets the user change the number of results to be displayed per page.

## Usage

Basic usage:

```html
<results-per-page-selector :options="[20, 50, 100]"></results-per-page-selector>
```

## Props

| Name    | Required | Type   | Default              | Description                       |
|---------|----------|--------|----------------------|-----------------------------------|
| options | false    | array  | `[6, 12, 24]`        | The different selectable options. |
| name    | false    | string | `'results_per_page'` | The select form input name.            |


## Slots

| Name    | Props  | Default        | Description   |
|---------|--------|----------------|---------------|
| default | option | `{{ option }}` | Option label. |

## CSS Classes

| ClassName                     | Description             |
|-------------------------------|-------------------------|
| alg-results-per-page-selector | The select input class. |
