# Command line

Typ is a command line tool. You can use it with the Windows Command Prompt, PowerShell, bash, and so on.

General usage is `typ [command] [arguments]`.

There is currently only one command, `typeset`.

### Linux

Note that it might be necessary to run Typ with elevated permissions (e.g. with `sudo`).

## Command line arguments reference

### General

| Argument | Alias | Effect |
| --- | --- | --- |
| `--inputFilepaths` | `-i` | List of Markdown files to use to create a formatted PDF. |
| `--outputFilepath` | `-o` | Output file path. |

Note that if `--inputFilepaths` is not specified, `typeset` will look for files in the working directory. This behavior is explained in more detail in [Projects](./projects.md).

### Configuration

Further configuration can be supplied through command line arguments. See [Configuration](./configuration.md).

### Example usage

`typ typeset -i text.md post-script.md -o myDoc.pdf --pageSize A4`