# Setting up your computer for Physics 67

We will be using [Jupyter notebooks](https://jupyter.org/) with the interactive [IPython](http://ipython.org/) enviroment to do the labs in this course.

Each week you will be working through 1-3 notebooks during the lab time, and then spending some additional time writing up a short report on what you did.


## Running these notebooks on your computer

To run these notebooks you are going to install 3 things on your computer.  Depending on the type of computer you have, the details are going to differ a bit, so we are just going to refer you to online installation guides.

You will need:

	1. A python installation and python package manager, typically this will be either:
	   1. miniconda (recommened)
		  1. You wil have to use the terminal window to install miniconda, it isn't complicated, but that might be new to some of you.
		  2. You will have to install a few extra data analysis packages by hand, again, it isn't complicated.
	   2. anaconda
		  1. You won't need the terminal window, and the installation will install all the packages you need (and a whole lot more)	
	2. The notebooks and data for this course
	   

### Option 1:  Installing 'miniconda'

The fastest way to get up and running is with [Miniconda](https://conda.io/en/latest/miniconda.html).
This will require that you do a number of things in the terminal window, but the instructions should be clear enough that you can set things up even if you haven't used a terminal window before.

Once you have installed and setup up miniconda, you can run this command in the terminal window to install the extra packages that you will need

	`conda install python=3.8 numpy scipy matplotlib` 


### Option 2: Installing 'anaconda'

The "Anaconda" data analysis enviroment is much more complete that miniconda, and includes some other things that you might find useful, but you certainly don't need it for this course

It does have the nice feature of complete environment, so you won't have to use the terminal to install anything.

You can download anaconda for free here:

https://www.anaconda.com/products/individual
https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html

This installation will include numpy, matplotlib, scipy and jupyter so you shouldn't have to do anything else.


### Installing and updating this Repository on your computer

### Option 1: using git (easy to do if you are comfortable using the terminal)

`git` is a software versioning tool.  It will allow you to fetch the latest version of the repository to your computer.
You can find instructions on how to install git here:

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Once you have installed git, from a terminal window you can do:

`git clone https://github.com/KIPAC/Physics67`

To install the repository on your computer.

Then at any point you can update the repository on your computer to the latest version by doing two commands

`git stash`

This will move all of the changes that you have made to a backup area.

`git pull`

This will fetch all the new changes form the repository and merge them into your version.


### Option 2: using github desktop app (a bit longer to setup, but easy to update each week)

1. Install the github desktop app from here: https://desktop.github.com/
2. Once you have installed it, click on the "Current Repository" box in the upper left corner.  This gives you a text box and a pull-down menu. 
3. Type in 'KIPAC/Physics67' into the test box and select "Clone Repository..." from the pull down menu
4. This will "clone" the repository onto your computer, for example putting it in "Documents/GitHub/Physics67"
5. At any point you can then update your local copy from the "origin" repository by clicking on "Fetch Origin" button.
6. This will show all the changes that you have made to your local version.  Git allows you do to many things, such as saving your local version and keeping track of the differences, but the simplest thing to do is either rename the files that you have changed or just to right-click on the little box next to the each file and select "Discard Changes"


### Option 3: by downloading it (easy, but you will have to manually update each week)

If you don't want to use git, you can always just download a snapshot of the repository.

Go to https://github.com/KIPAC/Physics67 and click on the green "Code" button in and select "Download ZIP" from the drop-down menu.

Note that this will download the current version of the repository, so you will want to do this each week before class.  You probably want to save the older version first so that you can refer to previous work.


## Opening Notebooks

If you installed jupyter using miniconda you can start jupyter from a terminal by typing:

`jupyter-notebook`

If you installed anaconda, then you can start jupyter from the App graphical interface.

One you have started jupyter, it will pop up a browser window showing the contents of what jupyter treats as your home folder.  (Either the folder you ran the `jupyter-notebook` command from, or a folder that you can set in the anaconda preferences.


## Backup plan, Running these notebooks using jupyter on the web. 

If for some reason you have issues installing the software on your computer, you can also use the service "binder" to run the notebooks on a remote server on the web.  This works, but has the disadvantage that it can be difficult to the work you do in the notebook, so you will probably end up copying things to 

1. Go to https://mybinder.org/
2. Type "KIPAC/Physics67" into the "GitHub repository name or URL" text box and then click on the orange "Launch" button, it will take a few minutes to set up a machine somewhere off in the cloud and connect you to it. 


### Opening a Notebooks in your brower

One you have started jupyter, it will pop up a browser window showing the contents of what jupyter treats as your home folder.  (What this is depends a bit on which 
