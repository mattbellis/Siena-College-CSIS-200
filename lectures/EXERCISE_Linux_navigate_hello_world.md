1. Log into [CoCalc](https://cocalc.com) (you might have to create a new account)
2. Create a "New Project"
  1. Give it the Title "Hello world"
  2. Give it the Description "My first exercise with Linux!"
3. Open up this Project
4. Create a "New" file (from the big "Create or upload a file" button).
  1. Name the file "myterminal" and "Select the type" to be ">_ Terminal"
  
Where are you?

    pwd 

Who are you?

    whoami

What files are in this directory?

    ls
    ls -l 

Upload a tar archive (similar to a zip file), with directories and files in it. 

1. Upload the necessary files for this exercise.
    1. Download [linux_hello_world.tgz](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/lectures/linux_hello_world.tgz) to your laptop.
    2. Upload it to your SageMathCloud project by
        1. Clicking on "+ New" 
        2. Uploading the file through the interface provided "Drop files to upload".
        3. Go back go "Files" (upper left)
        4. Click on "myterminal.term"
        

Unpack (actually untar) this file with the following command (hit "Enter" after you type that). 

    tar -zxf linux_hello_world.tgz

What files/directories do you have now?

    ls -ltr 

Your assignment now is to:
* Map out the files and directories under "project".
* Run any python scripts you find. 

        python FILENAME

* Look inside any data files you find. 
* What is the full path to the data files?
* Where do I need to book travel to?


Once the class has caught up to this point, follow along with the instructor and your "Linux cheat-sheet" to
* Make a copy of some of the files. 
* Delete some of these files. 
* Make a new directory.
* Remove that directory. 
* Edit a file using the [nano editor](http://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/). 
