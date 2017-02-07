Duroktar.github.io
==================

A blog for the kid in the corner with sweatpants.


Usage
-----

Install [**Lektor**](https://www.getlektor.com/) -

- **Python 2.7** (***not*** *Python 3.x*, also `python-dev`, `libssl-dev` and
`libffi-dev` is required on Ubuntu)
`sudo apt-get install python-dev libssl-dev libffi-dev`
- **ImageMagick** (`brew install imagemagick` can get you this on OS X and
`sudo apt-get install imagemagick` on Ubuntu the `imagemagick` package
needs to be installed. On Windows do `chocoinstall imagemagick`, which
requires [chocolatey](https://chocolatey.org/), or
[download from here](http://www.imagemagick.org/)).

Once you have those installed and have made sure that they are on your
`PATH`, you can get Lektor installed with an installation script:

    $ curl -sf https://www.getlektor.com/install.sh | sh

For Windows you can use the `command prompt`:

    C:\> @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex
     ((new-object net.webclient).DownloadString('https://getlektor.com/
    install.ps1'))" && SET PATH=%PATH%;%LocalAppData%\lektor-cli

but you can also do it directly in `Powershell`:

    PS C:\> iex ((new-object net.webclient).DownloadString('https://get
    lektor.com/install.ps1'))

**Clone repo**:

    git clone https://github.com/Duroktar/trabBlog.git

navigate to directory and from the `terminal` type:

    lektor server

Page can now be accessed in the browser at
[http://localhost:5000/](http://localhost:5000/)

About
-----

This is the main repository for my blog. Powered by Lektor.

