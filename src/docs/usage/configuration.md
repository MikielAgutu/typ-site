# Configuration

Typ is configured through a single YAML file, `config.yaml`.

The configuration file must be present in a Typ project. See [Projects](./projects.md) for more information about Project files.

## Configuration reference

### General options

| Option name | Description | Example |
| --- | --- | --- |
| `title` | The title of the document | `Alice in Wonderland` |
| `generateTableOfContents` | Whether to generate a table of contents based on headings | `true` or `false` |
| `printPageNumbers` | Whether to print page numbers | `true` or `false` |
| `printTitleMarginals` | Whether to print the chapter title in a top corner, and the document title in the bottom corner | `true` or `false` |
| `pdfTkPath` (optional) | Path to the PDFtk Server executable. See [Installation](./installation.md). | `C:\Programs\bin\pdftk.exe` |

### Formatting options

These options control what the formatting of the document looks like.

These options generally have an equivalent CSS property. For instance, `textLineHeight` maps to [`line-height`](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height), so could be set to `normal`, `2.5`, `3em`, and so on.

The links under the 'CSS' heading for each option have more information about valid values.

| Option name | Description | CSS | Example |
| --- | --- | --- | --- |
| `textLineHeight` | Sets the distance between lines of text | [`line-height`](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height) | `2.5` |
| `pageMargin` | The margin between the edge of the page and the content | [`margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin) | `10px` |
| `pageSize` | The size of the page | [`size`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page/size) | `A5`, `4in 6in` |
| `fontFamily` | Font for all text content. Currently supported fonts: `georgia`, `times new roman`, `arial` & `verdana` | [`font-family`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family) | `verdana` |

### Example `config.yaml`

```yaml
title: My document
fontFamily: Arial
pageSize: A5
pageMargin: 70pt 60pt 70pt
textLineHeight: 200%
fontSize: 12pt
generateTableOfContents: false
printPageNumbers: false
printTitleMarginals: false
pdfTkPath: C:\Programs\bin\pdftk.exe
```