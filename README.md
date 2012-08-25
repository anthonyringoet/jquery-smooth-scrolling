# Smooth Scrolling jQuery Plugin

## Demo & Examples

[http://mathiasbynens.be/demo/smooth-scrolling](http://mathiasbynens.be/demo/smooth-scrolling)

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

_– [Mathias](http://mathiasbynens.be/)_