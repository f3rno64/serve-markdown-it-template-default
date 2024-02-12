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

