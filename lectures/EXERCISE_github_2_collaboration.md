In this exercise, you will use Github to collaborate on a project with one of your classmates. You will each work on different parts of a program, fix them, and then use Github to share your work. 

Let's get started!

# Set up a repository

You have been paired up with another classmate. You are now collaborators on a very important software project. Congrats!

One of you has been assigned the alias [Ada](https://en.wikipedia.org/wiki/Ada_Lovelace) and the other person has been assigned the alias [Babbage](https://en.wikipedia.org/wiki/Charles_Babbage). This is how I will refer to you for the remainder of this exercise. 

Ada will create a Github repository called

         class_grades

When Ada has created the repo, she will add Babbage as collaborator. To do this from the webpage, go to **Settings --> Collaborators** and add Babbage by using his Github account name. When this happens, Babbage should see this repo appear from their main Github page. 

Babbage will then edit the README.md through the web interface to give some description of the project. 

Both Ada and Babbage will clone the repository so that they have a local version on their laptop. 

# The project

You will be writing code to read in grades from a text file and generate some simple statistics. You will use a common Jupyter notebook to run the code, but *each of you will write separate functions to do the actual computation*. 

## Get the starter files.

Babbage will download [this Jupyter notebook](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/lectures/EXERCISE_github_collaboration_notebook_COMPLETED.ipynb) and add/commit/push it to the repo. 

Ada will download [this data file of grades](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/lectures/grades1.csv) and add/commit/push it to the repo. 

Both Babbage and Ada should pull the updates to their laptops and open the notebook. 

## Write the functions

You will see the following lines in the notebook. 

          from adas_code import read_data
          from babbages_code import statistics

Each of you will use ***IDLE*** and create a file called either **adas_code.py** or **babbages_code.py** and in those file, put one function called *read_data* and *statistics*, respectively. You can figure out what these functions do from the Notebook description. 

Get it working!

If you find problems with each others code, put in a bug report and make sure those reports are closed out when the bug is fixed. 

## Next step...

If you get this working, check with your instructor for a new data file. 

Run over the new data file and make a histogram of the grades in the Notebook. 

