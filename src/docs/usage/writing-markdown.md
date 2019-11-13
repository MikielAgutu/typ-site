# Writing Markdown

When writing a document you want to spend most of your time on content, not formatting.

Typ allows you to write your document's content in a simple, lightweight text format called Markdown. 

With Typ, you can specify the important parts of your document's appearance, like font style and page size. Typ will combine your configuration with it's own sensible formatting style to produce a PDF.

You can learn more about how to write Markdown on [Markdown Guide](https://www.markdownguide.org/).

## Syntax highlighting

Typ supports syntax highlighting for Markdown code blocks.

In order to turn on syntax highlighting for a code block, you need to supply a language code.

For instance, for a C# code block:

```
 ```c#
 int x = 0;
 x++;
 Console.WriteLine(x);
 ```
```

### Syntax highlighting Markdown code reference

A table of supported languages and their codes is listed here.

| Language | Markdown code |
|----------|---------------|
| ASPX | `aspx` |
| C | `c` |
| C++ | `c++` |
| C# | `c#` |
| COBOL | `cobol` |
| Eiffel | `eiffel` |
| FORTRAN | `fortran` |
| Haskell | `haskell` |
| HTML | `html` |
| Java | `java` |
| JavaScript | `javascript` |
| Mercury | `mercury` |
| Pascal | `pascal` |
| Perl | `perl` |
| PHP | `php` |
| Python | `python` |
| Ruby | `ruby` |
| SQL | `sql` |
| Visual Basic | `visual basic` |
| VB Script | `vbscript` |
| VB.NET | `vb.net` |
| XML | `xml` |