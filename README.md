Demo: https://cadars.github.io/portable-php/

Get a single HTML document from a collection of Markdown files, and an RSS feed with the help of [portable-feed.php](https://gist.github.com/cadars/c1c2d4bad67e176ef833511385bc888c).

**Requirements:** PHP

1. Write posts in `content/`
2. Open `http://example.com/portable.php` in your browser
3. Save as `index.html`


Or from the command-line:

```
php portable.php > index.html
```

<details>
<summary>Included dependencies</summary>

<br>

- [Parsedown](https://parsedown.org/) converts Markdown to HTML.
- [ParsedownExtra](https://github.com/erusev/parsedown-extra) adds support for footnotes, abbreviations, definition lists, tables, `class` and `id` attributes, fenced code blocks, and Markdown inside HTML blocks.
- [ParsedownExtraPlugin](https://github.com/taufik-nurrohman/parsedown-extra-plugin) adds `loading="lazy"` to images, figure and figcaption elements, and more. Can be used for [syntax highlighting](https://github.com/taufik-nurrohman/parsedown-extra-plugin#custom-code-block-contents).

</details>
