[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/the-catalin/cat-coverflow)

# &lt;cat-coverflow&gt;

`<cat-coverflow>` is a [Polymer](https://github.com/Polymer/polymer) element that displays a coverflow with with many customizable properties.

## Demo

## [LIVE DEMO with Config Panel](http://webcomponents.online/cat-coverflow/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install --save cat-coverflow
```

Or [download as ZIP](https://github.com/the-catalin/cat-coverflow/archive/master.zip)

## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/cat-coverflow/cat-coverflow.html">
    <link rel="import" href="bower_components/cat-image/cat-image.html">
    <link rel="import" href="bower_components/cat-text/cat-text.html">
    ```

3. Start using it!

	```html
    <cat-coverflow>
        <cat-image src="http://webcomponents.online/images/01.jpg">
            <cat-text> Sample text </cat-text>
            <cat-text> Another sample text </cat-text>
        </cat-image>
        <cat-image src="http://webcomponents.online/images/02.jpg">
            <cat-text> Sample text </cat-text>
            <cat-text> Another sample text </cat-text>
        </cat-image>
    </cat-coverflow>
	```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

For detailed changelog, check [Releases](https://github.com/the-catalin/cat-coverflow/releases).

## License

[The MIT License (MIT)](https://opensource.org/licenses/MIT)

Copyright (c) 2017 Catalin Ungureanu