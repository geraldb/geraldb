# webcomponents sandbox


### Test Web Components

- `<x-reverse>`  see [reverse/index.html](http://geraldb.github.io/webcomponents/reverse/index.html) test page
- `<x-post>` see [post/index.html](http://geraldb.github.io/webcomponents/post/index.html) test page
- `<x-markdown>` see [markdown/index.html](http://geraldb.github.io/webcomponents/markdown/index.html) test page



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

