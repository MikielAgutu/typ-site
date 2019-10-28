# Installation

*Typ is currently only available for machines running 64 bit Windows. Other platforms are coming soon.*

Follow these steps to download and install Typ.

### Install Typ

- Download the Typ executable: {{ download_typ_button }}
- Unzip the folder and place it somewhere accessible on your machine (e.g `C:\Programs\Typ`)
- Navigate to the folder from a command line
- Run `typ` to check it works

To run Typ from anywhere on your machine, you must add it to your `PATH` environment variable.

- Amend your `PATH` environment variable to point to the directory containing `typ.exe`
    - For instance, `typ.exe` lives in `C:\Programs\Typ\typ.exe`, add `C:\Programs\Typ` to `PATH`
- Run `typ` from a command line to check it works

### Install PDFtk Server

Typ depends on a command line application called PDFtk Server.

Download and install [PDFtk Server](https://www.pdflabs.com/tools/pdftk-server/) following the instructions on their website. Ensure it's available on your `PATH`, which can be tested after installation by running `pdftk` from the command line.

Think this is annoying? PDFtk Server requires a paid license for redistribution. If you'd like to help improve Typ by sponsoring the redistribution license see [Contact](./contact.md).

