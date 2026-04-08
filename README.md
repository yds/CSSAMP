# [CSSAMP](https://cssamp.com)

A classless CSS framework for AMP HTML.

Go to [cssamp.com](https://cssamp.com) for examples and documentation.

## Quick start

### Option 1: Use the CSS source

1. Copy the contents of `cssamp.css` into your page's `<style amp-custom>` block.
2. Include whichever AMP component scripts your page needs.
3. Build your page with semantic markup and as few classes as possible.

### Option 2: Start from the embedded page

1. Copy `index.html` as your starting point.
2. Keep the AMP boilerplate and inline `style amp-custom` block in place.
3. Remove the demo sections and examples you do not need.

## Notes

- `cssamp.css` is the maintainable stylesheet source.
- `index.html` is the demo page and keeps an inline AMP-compatible copy of the same CSS.
- Form coverage includes AMP's `[submitting]`, `[submit-success]`, `[submit-error]`, and `visible-when-invalid` states to avoid abrupt layout collapse during submission.

## What's included

```text
CSSAMP/
|-- cssamp.css
|-- index.html
|-- LICENSE
`-- README.md
```

## Creator

__Morgan MacArthur__

- [https://github.com/morganmacarthur](https://github.com/morganmacarthur)
