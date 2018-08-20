
[![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

# NPRE 247 : Modeling Nuclear Energy Systems

This is the repository that holds ipython notebooks, python scripts, a 
syllabus, and other materials for Katy Huff's NPRE247 course at UIUC. 

## Syllabus

The syllabus will be kept up to date in this repository. It is subject to 
change, so please keep checking it.

## Running the Notebooks Locally

To run them on your own computer, where you can save changes, you will need to
install python and install git.

### Installing Python
 
Download and install the scientific python distribution called
[anaconda](https://www.continuum.io/downloads). You will need python version
3.0 or greater. 

### Installing Git (optional)

I recommend gaining access to the course notebooks via the version control
program, `git`. Instructions for installing git on different platforms can be
found [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### Acquiring the notebooks

**If you have installed git,** open a terminal program (or the Git Bash For Windows
program if you are on windows and execute the command:

```
git clone https://github.com/katyhuff/npre247.git
```

**If you have not installed git,** you can download the notebooks as a zip file
from [here](https://github.com/katyhuff/npre247/archive/master.zip). Then,
unzip the directory. 


### Running the notebooks 

You should now have a directory somewhere on your computer called npre247. Open
a terminal (or the git bash for windows program) and type the following command inside that directory:

```
jupyter notebook
```

Your browser should open to a localhost:8888 url. Navigate to the notebooks to
run, edit, and save them.

If you are on Windows and didn't install the Git Bash for Windows program,
follow these instructions [to run the
notebooks](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).


## Updating the notebooks

Periodically, I will make changes to the notebooks and add new ones throughout
the semester. If you have not installed git, you will need to re-download the
zip file. If you *have* installed git, navigate to your npre247 directory and
type the following:

```
git pull origin master
```

You may run into errors at this point if you have made edits and not committed
your changes.  Or, indeed, if you have made changes to the same lines to which
I have made changes, you may have a conflict. In either case, try to follow the
instructions that `git` gives you. Usually, it will tell you exactly what to
do.  If that's not enough, [here](http://swcarpentry.github.io/git-novice/) is
a great tutorial on using git effectively.
