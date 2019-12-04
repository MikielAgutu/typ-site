# Command line

Typ is accessed via a command line interface. You can use it with the Windows Command Prompt, PowerShell, and so on. 

General usage is `typ [command] [arguments]`.

There is currently only one command, `typeset`

## Command line arguments reference

| Argument | Alias | Effect |
| --- | --- | --- |
| `--inputFilepaths` | `-i` | List of Markdown files to use to create a formatted PDF. |
| `--outputFilepaths` | `-o` | Output file path. |

Note that if `--inputFilepaths` is not specified, `typeset` will look for files in the working directory. This behavior is explained in more detail in [Projects](./projects.md).

### Example usage

`typ typeset -i text.md post-script.md -o myDoc.pdf`