# Installation

Follow these steps to download and install Typ.

## Install Typ

- Click to download Typ:
    - {{ download_typ_latest_button_windows }}
    - {{ download_typ_latest_button_linux }}
- Extract the folder and place it somewhere accessible on your machine (e.g `C:\Programs\Typ`)
- Navigate to the installation folder from a command line terminal

### Windows users
- Run `typ` to check it works

### Linux users
- Make `typ` executable with `chmod`
    - `sudo chmod +x typ`
- Typ depends on Python 3 on Linux
    - It looks for Python 3 in `#!/usr/bin/python3`
- You may need to run Typ with elevated permissions (e.g. with `sudo`).
    - Run `sudo ./typ` to check it works
- Typ should work with most desktop distributions like CentOS, Debian, Fedora, Ubuntu, and derivatives
    - It may perform differently on other versions

### `PATH` environment variable

To run Typ from anywhere on your machine, you must add it to your `PATH` environment variable.

- Amend your `PATH` environment variable to point to the directory containing `typ.exe`
    - For instance, if `typ.exe` lives in `C:\Programs\Typ\typ.exe`, add `C:\Programs\Typ` to `PATH`
- Run `typ` from a command line terminal to check it works

### Install PDFtk Server (Optional)

Some features of Typ depend on a command line application called [PDFtk Server](https://www.pdflabs.com/tools/pdftk-server/).

Only follow this step if you know you want to use a feature that depends on PDFtk Server. If you're just getting started with Typ, it's best to skip this step.

#### Instructions

Download and install [PDFtk Server](https://www.pdflabs.com/tools/pdftk-server/) following the instructions on their website. Ensure it's available on your `PATH`, which can be tested after installation by running `pdftk` from the command line.

If you don't want to add PDFtk Server to your `PATH`, you can use the [`pdfTkPath` Configuration option](./configuration.md).

Think this is annoying? PDFtk Server requires a paid license for redistribution. If you'd like to help improve Typ by sponsoring the redistribution license see [Contact](..\contact.md).

