By now you should have downloaded the appropriate LaTeX distribution for your computer. You can find more 
details on the [Install Notes](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/HOWTO_INSTALL.md)
on this course site. 

Once you have installed LaTeX, you will want to open up an editor. This is where you will write your LaTeX document and then have it coverted to a slick-looking PDF. The editors are
* Windows - [TeXWorks](https://www.tug.org/texworks/)
* Mac - [TeXShop](http://pages.uoregon.edu/koch/texshop/texshop.html)

Open these programs up either from an icon on your desktop or by using the Search function, depending on how your computer has installed the programs. 

## First test 

For the first step, you will create the simplest LaTeX document by following these steps.

* Create a new **Folder** under your **CSIS200** folder (or whatever you named it) called *firstlatex*. 
* From your LaTeX editor, open a *File --> New Document* and type the following in the editor.
    
        \documentclass[]{article}
             
        \begin{document}
             
           Hello world!
     
        \end{document}

* Click **File --> Save As** and save it in your **firstlatex** folder with the name 

         myarticle.tex

* Next you want to "compile" it, which means convert it to a PDF file. You can do this by pressing either the green button (TeXWorks) or the *Typeset* button (TeXShop). 
* If everything has worked, you will see a plain PDF with the words "Hello world!"

# Compiling a bigger document. 

* Create a new **Folder** under your **CSIS200** folder called **articletemplate**.
* Download [article_template.tex](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/lectures/article_template.tex) and save it in this new directory. Make sure the file is named "articletemplate.tex"
* Compile it! If it doesn't work, check with the instructor.

# Compiling a journal article. 

* Create a new **Folder** under your **CSIS200** folder called **journaltemplate**.
* Download [cms_higgs.png](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/lectures/cms_higgs.png) and [journal_article_template.tex](https://github.com/mattbellis/Siena-College-CSIS-200/blob/master/lectures/journal_article_template.tex) and move both of them to this new directory. Make sure the files are named as they are here. 
* Compile it! If it doesn't work, check with the instructor. 

   When you have compiled the journal article, upload it to the Assignment for this on the Classroom site. This will ***not*** be graded, but it will allow me to see who was successful with the installation and testing. Next class, we will begin to learn more about the typesetting power of LaTeX!



