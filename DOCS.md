# HTMLQuery Docs

## Installation

- Add the framework to your project:

```html
<body>
    ...
    <script src="https://flashinc.lachlanjowett.com/cdn/htmlquery.min.js">
    </script>
</body>
```

- Read the docs and off you go!

## Usage

There are two main ways to use HTMLQuery:

1.

``` js
    new $()
```

2.

``` js
    new HTMLQuery()
```

You can choose whichever one you prefer.

There are a few parameters you can pass to the class:

``` js
// Base query
new $('<query selector>')
// Selectors
// ID
new $().id('<id>')
/* or */
new $().i('<id>')
// Class
new $().class('<class>')
/* or */
new $().c('<class>')
// Query
new $().query('<query selector>')
/* or */
new $().q('<query selector>')
// Tag
new $().tag('<html element>')
/* or */
new $().t('<html element>')
// Name
new $().name('<name>')
/* or */
new $().n('<name>')
// QueryAll
new $().queryAll('<query selector>')
/* or */
new $().qa('<query selector>')
```
