# Projects

Typ expects a certain set of files to exist in order for it to work. Together, these files are called a 'Project'.

This page explains how to configure a Project.

## Creating a Project

- Create a new directory for your Project somewhere on disk
    - It's recommended that Typ Project files have their own exclusive directory
- Inside the Project directory, create files that match the file names and formats listed on this page
- Note that the file names should exactly match the documentation

## Project file reference

This table explains the purpose of each Project file. 

| File | Description | optional |
| --- | --- | --- |
| `text.md` | The content of the book | false |
| `config.json` | Configuration for how the book should be produced. See [Configuration](./configuration.md) for details about each configuration option. | false |
| `preamble.md` | The information displayed after the front cover. Could contain copyright details, author information, etc. | true |
| `front-cover.png` | The front cover image of your book | true |
| `back-cover.png` | The back cover image of your book | true |