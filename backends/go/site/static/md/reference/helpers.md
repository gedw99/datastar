# Action Plugins

[Source](https://github.com/delaneyj/datastar/blob/main/packages/library/src/lib/plugins/helpers.ts)

## `$$setAll(regexp: string, value: any)`

```html
<div data-on-change="$$setAll('contact_', $selections.all)"></div>
```

Sets all the signals that start with the prefix to the value of the second argument. This is useful for setting all the values of a form at once.

## `$$toggleAll(regexp: string)`

```html
<div data-on-click="$$toggleAll('contact_')"></div>
```

Toggles all the signals that start with the prefix. This is useful for toggling all the values of a form at once.

## `$$clipboard(text: string)`

```html
<div data-on-click="$$clipboard('Hello, world!')"></div>
```

Copies the text to the clipboard. This is useful for copying text to the clipboard.
