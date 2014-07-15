# connect-fonts-alegreyasans

Alegreya Sans Black fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-alegreyasans");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/alegreyasans-black/fonts.css" type="text/css" rel="stylesheet"/ >
```

Multiple fonts from the family can be included by using a comma separated list of fonts:
```html
<link href="/alegreyasans-black,alegreyasans-blackitalic,alegreyasans-bold,alegreyasans-bolditalic,alegreyasans-extrabold,alegreyasans-extrabolditalic,alegreyasans-italic,alegreyasans-light,alegreyasans-lightitalic,alegreyasans-medium,alegreyasans-mediumitalic,alegreyasans-regular,alegreyasans-thin,alegreyasans-thinitalic/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available fonts:
* alegreyasans-black
* alegreyasans-blackitalic
* alegreyasans-bold
* alegreyasans-bolditalic
* alegreyasans-extrabold
* alegreyasans-extrabolditalic
* alegreyasans-italic
* alegreyasans-light
* alegreyasans-lightitalic
* alegreyasans-medium
* alegreyasans-mediumitalic
* alegreyasans-regular
* alegreyasans-thin
* alegreyasans-thinitalic

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/alegreyasans-black/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin

5. Set your CSS up to use the new font by using the "Alegreya Sans Black" font-family.
```
    body {
      font-family: 'Alegreya Sans Black', 'sans-serif', 'serif';
    }
```

## Font Info
Alegreya Sans

* Copyright: Copyright (c) 2013 by Juan Pablo del Peral (huertatipografica.com.ar)
* Designer: Juan Pablo del Peral
* Designer URL: http://www.huertatipografica.com.ar
* Vendor: Huerta Tipografica
* Vendor URL: http://www.huertatipografica.com.ar

## Development Info

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL

