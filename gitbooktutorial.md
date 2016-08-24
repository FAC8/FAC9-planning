#How to use GitBook


**GitBook is awful to use but nice to read. This tutorial will hopefully make it less painful for future cohorts. The gitbook site can be found [here](https://www.gitbook.com/)**

##Creating a GitBook for the next cohort.

1) Ensure that you have been invited into the FAC organisation on gitbook and have been given admin rights there. This is necessary in order to create a gitbook from a Founders & Coders github repository.

2) Sign into gitbook, through your gitbook or github account, go to the top right-hand menu, and go to the Founders & Coders organisation.

3) There will be a list of existing gitbooks. Find the most recent gitbook (that was used for your cohort) and go into it.

4) On the gitbook's root page select the dropdown menu next to edit. There will be a link you can use to clone the gitbook's repo.

5) Clone the gitbook's repo onto your local machine. In the terminal you will be asked to provide your account name and password. It's asking for your gitbook account name and password not your github details, so ensure that you have a gitbook account.  

4) Now that you have cloned the prior cohort's gitbook, initialise a github repository in the relevant github organisation using this clone.

5) Sign into gitbook and select the new button on the top menu bar to begin creating a new gitbook.

6) From the main drop-down menu on the creation screen select the option to import and sync an existing Github repository. Make sure on the drop-down menu beneath this that you are creating this through the Founders & Coders organisation and not your own individual account. Give it a title, description and select the repository you have just created on github to sync it with. Then click "Create Book"!

7) The gitbook is now created and can be found on the Founders & Coders organisation on gitbook. It will have the same folder structure and content as the last cohort's gitbook, and be synced with the repository you created for it on github. :-)

##Creating a file on the GitBook

Next you want to create some new files. "That's easy!" I hear you say, but no. GitBook has made this very simple sounding task as annoying as possible.

For simplicity's sake it is advised to re-use the folder structure of prior gitbooks.

1) Find your new gitbook through the founders & coders organisation on gitbook and go into it.

1) Select the edit button. You will be taken to a CMS with two file directories that you can see. On top is the one that is displayed in the book and below are the actual .md files from the github repository you created the book from.

2) Create a new file under the appropriate folder on the bottom directory by right clicking the folder and selecting "new file." Name it whatever you like. "learning-outcomes.md" for example.

3) Then on the top directory, right click on the folder you want that file displayed in and create an article with the name that you want to have displayed under that week. "Learning Outcomes" for example.

4) And now you need to *link* these files in the two directories. Right click the article you just created and select "Edit pointing file". Point that to the .md file you want to link it to.

5) Great success. Remember to save your changes if you are editing existing files.

The files that you see in gitbook's editing mode are in sync with those in the repo the gitbook was created from and will update that repo automatically with your changes. Vice versa if you update the repo.
