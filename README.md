# webcomponents sandbox


### Test Web Components

- `<x-hello>`  see [hello/index.html](http://geraldb.github.io/webcomponents/hello/index.html) test page
- `<x-reverse>`  see [reverse/index.html](http://geraldb.github.io/webcomponents/reverse/index.html) test page
- `<x-post>` see [post/index.html](http://geraldb.github.io/webcomponents/post/index.html) test page
- `<x-markdown>` see [markdown/index.html](http://geraldb.github.io/webcomponents/markdown/index.html) test page


### Test Basic Machinery

- [`basic1.html`](http://geraldb.github.io/webcomponents/basic1.html)
- [`basic2.html`](http://geraldb.github.io/webcomponents/basic2.html)
- [`basic3.html`](http://geraldb.github.io/webcomponents/basic3.html)
- [`template.html`](http://geraldb.github.io/webcomponents/template.html)
- [`shadowdom.html`](http://geraldb.github.io/webcomponents/shadowdom.html)
- [`supports.html`](http://geraldb.github.io/webcomponents/supports.html)



###  HTML Imports Browser Check

To check if your browser supports HTML imports use this snippet
to check if `.import` exists on the `<link>` element:

```js

function supportsImports() {
  return 'import' in document.createElement('link');
}

if (supportsImports()) {
  // Good to go!
} else {
  // Sorry, it's time to get a better browser e.g. install Chrome 36+!
}
```

