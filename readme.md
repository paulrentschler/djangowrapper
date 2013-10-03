# djangowrapper

Bash shell scripts for working with Django projects in virtualenv environments.

## Dependencies

  * virtualenv
  * pip
  * virtualenvwrapper


## Installation

  1. Install the dependencies
  1. Ensure the WORKON_HOME environment variable is defined in .bashrc
  1. Clone the project into ~/djangowrapper
  1. Copy the packages.dist file to packages.local and add any additional
     packages you want installed into each virtualenv
  1. Create a settings.tpl file (optional) and include any settings that
     you want to use in the Django settings.py file. This file will be
     prepended to the settings.py file and you will have to put the
     lines where they need to go in the file


## Usage

To create a new virtualenv with a new Django project issue:

    ~/djangowrapper/mkdjangoproject virtualenv_name project_name

