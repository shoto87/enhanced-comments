# Enhanced Comments

A simple VS Code extension to color and categorize your comments more meaningfully.

## Supported Comment Prefixes

- `//%` → Yellow: Bug
- `//!` → Red: Error
- `//+` → Blue: Suggestion / Improvement
- `//?` → Purple: Question
- `//*` → Green: Highlight
- `//~` → Gray: Deprecated

## Example

```js
//% This needs fixing
//! Crashes if input is null
//+ Consider using a cache here
//? Why is this check needed?
//* Important logic below
//~ Old method — remove later
```
