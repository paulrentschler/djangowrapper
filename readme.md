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


## License

Copyright Paul Rentschler. All Rights Reserved.

Permission to use, copy, modify, and distribute this software and its
documentation for any purpose and without fee is hereby granted, provided 
that the above copyright notice appear in all copies and that both that 
copyright notice and this permission notice appear in supporting 
documentation, and that the name of Paul Rentschler not be used in 
advertising or publicity pertaining to distribution of the software 
without specific, written prior permission.

PAUL RENTSCHLER DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE, 
INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS, IN NO EVENT 
SHALL PAUL RENTSCHLER BE LIABLE FOR ANY SPECIAL, INDIRECT OR CONSEQUENTIAL 
DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, 
WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING 
OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

