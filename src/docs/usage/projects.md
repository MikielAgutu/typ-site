# Projects

For a work that consists of multiple files (front cover, multiple chapter files, preamble, etc), these should be stored in a single folder, termed a Project.

A Project is just a normal folder on your file system that contains files that Typ can work with.

Typ will consider the working directory to be a Project folder. Therefore, it's best to use a single folder for the exclusive use of Typ if you plan to use multiple files.

## Creating a Project

Create a new folder somewhere on the file system. This will be the Project folder.

Add Markdown files for the content of your document. Ensure each file has a `.md` file extension.

You may also choose to add a configuration file, `config.yaml`. See [Configuration](configuration.md).

### Reserved file names

There are certain file names that have special meanings in Typ. If present in your Project, Typ will automatically pick them up and use them.

For instance, to add a cover image to your document, just add a file called `front-cover.png` to your Project.

See the Project file reference at the end of this page for details.

## Projects and the command line

When you run `typ typset` in a Project, Typ will do the following:

- Find all the files that end in the `.md` extension
- Combine the files in alphabetical order
- Pick up any files with reserved file names
- Create the PDF

## Reserved Project file name reference

This table explains the purpose of each Project file. 

| File | Description | optional |
| --- | --- | --- |
| `*.md` | The content of the document | false |
| `config.yaml` | Configuration for how the document should be produced. See [Configuration](./configuration.md) for details about each configuration option. | true |
| `preamble.md` | The first content page. Could contain copyright details, author information, etc. | true |
| `front-cover.png` | The front cover image of your document | true |
| `back-cover.png` | The back cover image of your document | true |