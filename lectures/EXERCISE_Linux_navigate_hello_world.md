1. Log into [SageMathCloud](https://cloud.sagemath.com/)
2. Create a "New Project"
  1. Give it the Title "Hello world"
  2. Give it the Description "My first exercise with Linux!"
3. Open up this Project
4. Create a "New" file.
  1. Name the file "myterminal" and "Select the type" to be ">_ Terminal"
  
Where are you?

    pwd 

Who are you?

    whoami

What files are in this directory?

    ls
    ls -l 

Run the following command. This will download a tar archive (similar to a zip file), with directories and files in it. 

    wget https://goo.gl/Lcm2oR -O linux_files.tgz 

Unpack (actually untar) this file with the following command. 

    tar -zxf linux_files.tgz

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
* Edit a file using the [pico editor](https://www.cs.colostate.edu/helpdocs/pico.html) or [nano editor](http://mintaka.sdsu.edu/reu/nano.html). 
