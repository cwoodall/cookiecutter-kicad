# cookiecutter-kicad

[Cookiecutter](https://github.com/audreyr/cookiecutter) template for a KiCad project.

## Features

* Creates a basic KiCad project with schematic and PCB files.
* Creates a documentation directory with a [MkDocs](http://mkdocs.org)

## Usage

Generate an KiCad product directory:

    cookiecutter https://github.com/cwoodall/cookiecutter-kicad.git

Then:

* Create a repo and put it there.
* To deploy the application you have two options:
  1. Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
  2. Download and install `mkdocs` using `pip` and use `mkdocs gh-deploy` which
     will deploy the documentation as a github page
