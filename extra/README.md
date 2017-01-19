# packagename
 (Package name)

Description

The code runs with Python 2.x since its uses wxpython (not
yet officially ported to Python 3).
The code has been developed on Ubuntu Linux. It runs also on Mac OS-X.

INSTALLATION NOTES

To install the code in your computer, you need first to install the anaconda
python (https://www.continuum.io/downloads).
You will have to use the Python 2.x distribution since the code
uses wxpython which is still not ported to Python 3.


Then clone the repository:
git clone https://github.com/repositoryname/packagename.git

Build the conda package:
conda build packagename

And install it locally:

conda install --use-local sospex

At this point you can start the code everywhere by
typing:

packagename

since the executable is in the ~/anaconda/bin directory.
