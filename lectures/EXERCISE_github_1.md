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

# Make some changes. 
