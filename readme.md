# css-ui
[![npm](https://img.shields.io/npm/v/@lcf.vs/css-ui.svg?style=plastic)]()

A pure CSS base to make a responsive user interface.

* Accessible
* Flexible
* Classes/ids non-dependant
* No JavaScript required
* No non-semantic tags
* No hacks
* No browser specific media queries
* Easy to install

[Demo](https://lcfvs.github.io/css-ui/)

## Install

### Using NPM
`npm install @lcf.vs/css-ui --prefix site-dir/assets/css`

### Using a CDN
```html
<link href="https://cdn.rawgit.com/Lcfvs/css-ui/2.0.1/css-ui.min.css" media="screen" rel="stylesheet" /> 
```

```html
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="UTF-8">
        <title>Basic layout - css-ui</title>
        <link href="assets/css/style.css" media="screen" rel="stylesheet" />
        <meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no" />
    </head>
    <body>
        <header>
            <h1>css-ui</h1>
        </header>
        <nav>
            <a href="javascript:" rel="noopener noreferrer" tabindex="1">☰</a>
            <a href="javascript:" rel="noopener noreferrer" tabindex="-1">⬅</a>
            <ol>
                <li><a href="/">Home</a></li>
            </ol>
        </nav>
        <main>
            <h1>css-ui basic layout</h1>
            <section>
                <h1>Section title</h1>
                <p>Section content</p>
            </section>
        </main>
    </body>
</html>
```

## License

[MIT](https://github.com/Lcfvs/css-ui/blob/master/licence.md)

## Contributions

A special thanks to [ascito](https://github.com/ascito) for some improvements. =)

## Compatibility

* PC
    * Firefox
    * Chrome
    * IE 11
    * Edge
    * Opera
    * Yandex

* Mobile
    * Firefox
    * Chrome
    * Safari
    * Samsung
    * UC Browser
    
* Mac
    * Firefox
    * Safari
    * Chrome

All the compatibility tests are made on [<img height="36px" src="./Browserstack-logo.svg" />](https://www.browserstack.com)
