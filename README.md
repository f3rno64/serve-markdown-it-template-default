# http-server-md-template-default

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

Simple default template for `http-server-md`, supporting multiple color
themes and configurable syntax highlighting.

> README & DOCS TODO

### [Installation](#installation)
![npm badge](https://nodei.co/npm/http-server-md.png?downloads=true&downloadRank=true&stars=true)

```bash
pnpm add http-server-md-template-default
```

### [Developing](#developing)

```bash
pnpm gen-readme // update README.md
pnpm docs // update DOCUMENTATION.md
pnpm test // lint & mocha
pnpm update-deps // bump all deps
```

### [Release History](#release_history)

See *[CHANGELOG.md](CHANGELOG.md)* for more information.

### [License](#license)

Distributed under the **MIT** license. See [LICENSE.md](LICENSE.md) for more information.

### [Contributing](#contributing)

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

---

## [API Reference](#api_reference)

> The standalone JSDoc reference can be found in [DOCUMENTATION.md](DOCUMENTATION.md)

## Modules

<dl>
<dt><a href="#module_http-server-md-template-default">http-server-md-template-default</a></dt>
<dd><p>Simple default template for <a href="https://github.com/f3rno64/http-server-md">http-server-md</a>, supporting
multiple color themes and configurable syntax highlighting.</p>
</dd>
</dl>

## Functions

<dl>
<dt><a href="#genImageMarkdown">genImageMarkdown(params)</a> ⇒ <code>string</code></dt>
<dd><p>Generate a markdown string to display an image at <code>relPath</code>.</p>
</dd>
</dl>

<a name="module_http-server-md-template-default"></a>

## http-server-md-template-default
Simple default template for [http-server-md](https://github.com/f3rno64/http-server-md), supporting
multiple color themes and configurable syntax highlighting.

**License**: MIT  
<a name="genImageMarkdown"></a>

## genImageMarkdown(params) ⇒ <code>string</code>
Generate a markdown string to display an image at `relPath`.

**Kind**: global function  
**Returns**: <code>string</code> - md  

| Param | Type | Description |
| --- | --- | --- |
| params | <code>object</code> | params |
| params.relPath | <code>string</code> | path relative to content root path. |
| params.name | <code>string</code> | image alt text. |



<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/http-server-md-template-default.svg?style=flat-square
[npm-url]: https://npmjs.org/package/http-server-md-template-default
[npm-downloads]: https://img.shields.io/npm/dm/http-server-md-template-default.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/f3rno64/http-server-md-template-default/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/f3rno64/http-server-md-template-default
