# Set up your Linux environment

1. Log into [SageMathCloud](https://cloud.sagemath.com)
2. Create a "New Project"
    1. Give it the Title "Python and shell scripts"
    2. Give it the Description "Running Python from shell scripts"
3. Open up this Project
4. Create a "New" file.
    1. Name the file "myterminal" and "Select the type" to be ">_ Terminal"

# Python and command line options

1. Referring to your previous work, write a Python script (program) that calculates pi using
Monte Carlo methods.
    1. Use only 10000 random numbers. 
    2. *Do not* print out any of the plots. 
2. Follow the instructor and use the [sys module](https://docs.python.org/2/library/sys.html) to add command-line options. 

         import sys
         
         print len(sys.argv)
         for a in sys.argv:
             print a
             print type(a)
             
          #npoints = int(sys.argv[1])
          #if npoints>1e7:
          #    print "Too many points! Must be less than 10M"
          #    exit()
          
3. Once you have understood what is happening and uncommented the necessary lines, run the script
with different numbers of points. 

          python calc_pi.py 100
          python calc_py.py 10000
          

# Shell scripts

1. Create a file called **run_script.sh** and put in the following lines. *Made sure you don't have any spaces on that first line!*

          n=1000000
          python calc_py.py $1
          python calc_py.py $1
          python calc_py.py $1
          python calc_py.py $1
          python calc_py.py $1
          python calc_py.py $1
          python calc_py.py $1
  
2. Run this script by executing the following command on the Linux command line. 

         sh run_script.sh
