# Getting started

Typ is a simple typesetting application.

It allows you to turn plain Markdown into a formatted PDF ready for print. It is accessed through a command line interface.

## Your first book

First install Typ. See [Installation](./usage/installation.md).

Next, you need to create a Project. This is where your book's files will live.

Create a new folder on your machine. Inside the folder create the following files:

- `text.md`
- `preamble.md`
- `config.json`

Open `text.md` and write something. If you need inspiration, copy this:

```markdown
# Chapter 1 - Down the Rabbit Hole
Alice was beginning to get very tired of sitting by her sister on the bank, and of having nothing to do: once or twice she had peeped into the book her sister was reading, but it had no pictures or conversations in it, ‘and what is the use of a book,’ thought Alice ‘without pictures or conversations?’
```

Open `preamble.md` and write your name and the current date. Something like this:

```markdown
Joe Bloggs

21/10/2019

*All rights reserved*
```

Finally, configure your Project. Open `config.json` and paste in the following:

```json
{
  "title": "Alice in Wonderland",
  "fontFamily": "Arial",
  "pageSize": "A5",
  "pageMargin": "70pt 60pt 70pt",
  "textLineHeight": "200%",
  "fontSize": "12pt",
  "generateTableOfContents": true 
}
```
Finally, it's time to run Typ. Open a command line terminal and navigate to your Project folder. 

Run `typ typeset` from the command line.

Your ready-to-print PDF will be created and placed in the Project directory. See [Command Line](./usage/command-line.md) for more information.

### Add cover images

Typ supports front and back cover images.

Download the two sample images [`front-cover.png`](./front-cover.png) and [`back-cover.png`](./back-cover.png).

Place these two files in your Project folder.

Run `typ typeset` again. Typ will automatically pick up the cover images and add them to your book.

That's it! You're now ready to begin creating books.

### Further reading

To do more with Typ, you'll want to read these pages:

- [Projects](./usage/projects.md)
- [Configuration](./usage/configuration.md)
- [Writing Markdown](./usage/writing-markdown.md)