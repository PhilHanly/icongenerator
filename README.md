# Icon Generator

A free icon generator for aNewSpring activities. Pick a style (Line, Duotone, Badge or Soft), a colour and a line weight, then download any icon as a transparent PNG (78, 128, 256 or 512 px) or SVG, or download the whole set as a ZIP.

All 55 icons are original SVG drawings on a 24 px grid. Everything runs in the browser; there is no server or build step.

## Run it locally

Open `index.html` in any modern browser.

## Add an icon

Icons live in the `ICONS` array in `index.html`. Each entry is:

```js
["Name", "search keywords", `<svg inner markup on a 24 x 24 grid>`]
```

Use `class="f"` on shapes that should take the tinted fill in Duotone and Soft styles, and `class="d"` on small solid dots.
