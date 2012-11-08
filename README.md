# Smooth Scrolling jQuery Plugin
Can be used with fixed header.

## Example Usage

### Simple – Inside entire document

Find all links to anchors in the same document, and make them scroll smoothly when clicked:

```js
$('html').smoothScroll();
```

### Simple – Inside a specified element

Find all links to anchors in the same document inside `#content`, and make them scroll smoothly when clicked:

```js
$('#content').smoothScroll();
```

### Specifying options
Possible options are animation speed and offset for fixed position headers. These settings default to the settings as seen below.

```js
$('html').smoothScroll({
	speed: 400,
	offset: 0
});
```

I forked this repo. The original plugin was made by [Mathias](http://mathiasbynens.be/).

## Caveats
- Doesn't work when scrolling to `name` attributes.
- Use `body` as main element in selector on which you call `smoothScroll()` because Chrome has issues when you use `html`.