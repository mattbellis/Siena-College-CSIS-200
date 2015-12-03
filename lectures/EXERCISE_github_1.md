In this exercise you will set up a very simple repository on Github, clone it to your laptop, make some changes, and then push those changes back to Github. 

Let's get started!

# Make a repository on Github. 
1. Go to Github and sign in. 
2. Click the Green button that says **+ New repository**.
  1. Name the repo "hello_world"
  2. Give it the description "My first Github repo!"
  3. Keep it *Public*
  4. Click the radio button to **Initialize this repository with a README**. 
  5. Click the green button **Create repository** at the bottom. 

# Clone the repository to your laptop. 
1. Open a Git Bash window (Windows) or Terminal (Mac). 
2. Navigate to your *Desktop*. It will be something like...

         cd Desktop

3. Make a new directory here to hold your repositories.

         mkdir github_repos

4. Clone (copy over) the repository from Github. To do this, you will need to get the URL of the repo on Github. 
  1. On the repo website (on Github), find the button that says either **HTTPS** or **SSH** and select (if it is not already) **HTTPS**.
  2. Highlight (in preparation for copying it) the text next to it. Something like "https://github..." You can Ctrl-c it, just in case it works on your laptop. 
  3. Go back your Git Bash/Terminal window and type the following, replacing the URL with your own. 

          git clone https://github.com/mattbellis/hello_world.git

# Add a file and commit it to your local (on your laptop) repo
1. Create an empty file with the *touch* command.

          touch test_file.tmp

2. Add it to your ***local*** (on your laptop) repo. 

          git add test_file.tmp

3. Commit it to your ***local*** repo. We will give it a message with the *-m* option. 

          git commit -m "Added a new file that is empty for now." test_file.tmp

# Push it back to Github
1. Copy all this information and new file back to Github

          git push

2. You may be prompted for your Github username and password. 
3. Check on the website to see if both the file and the commit message show up!

# Edit using the website
1. On the website, select the file **test_file.tmp**.
2. Find the Edit button that looks like a pencil positioned at an angle with a positive slope. 
3. Click it and edit the file. Just add some text.
4. When you are done, click the green **Commit changes** button at the bottom. 

# Pull those changes back to your laptop
1. Go back your Git Bash/Terminal window and type the following

          git pull

2. Check to see if the contents of the file has changed using the usual Linux commands. 

          cat test_file.tmp

# Make a change you don't want.
1. From the website, add the following text to the test_file.tmp

         These are words which I don't want to keep. 

2. When you commit it (green button at bottom), add a comment along the lines of "This is a mistake".
3. Pull these change to your lapt and look in *test_file.tmp* to verify that your words got added. 

# Go back to an earlier version (undo your edits)
1. On your laptop type
 
         git status
  
   1. Do you understand this output?
2. Now type

         git log
   1. You will see a lot of output that looks like this...

'''shell
commit 99518bef2e954aa650abc271a5ebc57df4de51d8
Author: Matt Bellis <mbellis@siena.edu>
Date:   Thu Dec 3 00:42:16 2015 -0500
 
   Update test.tmp
 
   I don't think I want this info.
'''
3. These are all versions of your edits and commits. Do you see the most recent one? The mistake? 
4. Let's go back one edit. The really long list of numbers and words is a [hash](https://en.wikipedia.org/wiki/Hash_function) which provides a unique identifier for the changes. Find the hash associated with the older edit. When you do, type this on your laptop. 

         git checkout HASH test_file.tmp

5. Look inside the file and it should be back to how it was!

You don't need to do the edits on the Github site to undo these changes. You can do the same thing with all the work and the commits you do on your laptop. 
