# Developer tools for the fertilized library

This project is intended to be used with the
[fertilized-forests](https://github.com/classner/fertilized-forests) library.
Simply clone it into the root folder of the library, so that the folder
structure is `fertilized-forests/fertilized-devtools`. It is automatically
ignored by git.

## Requirements

The code generator is written in Python. It has few required packages that
can be installed by running

    pip install -r requirements.txt

from the `fertilized-devtools` folder.

## Usage

To update the serialization code and all interfaces, go to the
`binding_generator` folder (important, it is not relocatable!) and run

    python generate.py

For general development information, consult the
[developers guide](http://www.multimedia-computing.de/fertilized/pages/developers-guide.html).
