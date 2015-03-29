#media-image

> This component will load an image only if it matches the screen size.

---

### Markup

```html
<img data-component="media-image" data-src="http://my/image/url.ext"  data-media-min="400" data-media-max="800" />
```

## Optionals

| options       |     default      |        values
|:--------------|:----------------:|:-----------------
|data-media-css|    null          |  `string` A css class name used on image when media matches.