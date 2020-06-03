                                                       IS117-450: A03

Step-by-step tutorial: 
GIT:
1. Go onto https://git-scm.com/downloads, to download git as a local program.
2. Install the git file by double clicking on the downloaded file.
3. This is a required plugin for Webstorm, so it has to be installed. 
4. Once git is installed, open Webstorm.
5. To display the Webstorm settings, press "Ctrl+Alt+S" and choose Version Control then Git from the left side.
6. Click "Test" to make sure that Webstorm is connected to Git.
7. The path in the location box should be auto detected. 
8. If Git is installed correctly, you should get the message “Git Executed Successfully.” 
9. Click "OK" to exit.

GITHUB:
1. Go onto https://github.com and create an account.
2. Once you signin, you can click on the green "NEW" button to create a repository, which is a folder for a project. 
3. When you click on the green button, you will get the options to add a repository name, add a description for the project, make the project either public or private, and to add a README file.
4. Once all this information is added, you can click on the "create repository" button at the end.
5. Once the repository is created, you can add files into the repository by clicking on the "create new file" on the right side next to "upload files" button. 
6. Clicking create new file, you will be taken to another page, where you can add a name for the file along with an extension of that file at the end of the name. 
7. Next, you can add the code or text in the box below the name box. 
8. Under the edit new file box, you can find the commit new file area. In that area, you can add a description and a title for the commit made. 
9. Once everything is done, you can click on the "commit new file" button. 
10. You can create new files this way each time. 
11. When you want to add this project onto your local computer, you can download or clone the folder by clicking on the "clone or download" green button on the right hand side. 

WEBSTORM:
1. Go onto https://www.jetbrains.com/community/education/#students website.  
2. Scroll down to "Individual licenses for students and teachers" section and click on the "apply now" button. 
3. Once you click on that and enter all the information, you will get an email to verify and activate the key for the free version.
4. Once it is ready, you can download the webstorm for your computer. 
5. In Webstorm press "Ctrl+Alt+S" for system preferences and select version control Git and enter the path to the git.exe to connect git and to connect github account. 
6. Next, it will ask for the user and password for the github account. 
7. Once it is authenticated, it will connect github account with webstorm so you can add projects onto github.com.
8. We can start creating projects from Webstorm, by clicking “Create New Project” onthe Webstorm main page.
9. It will open up the box to name and to add the location for the project, once that is done, you can click on "Create".
10. We can then create files by choosing File then New then HTML File then HTML 5.
11. Then we have to name the file and it should be in lowercase.
12. Once that is done, you can start writing code and edit it in the code box. 
13. Files can also be added to git when "Add to Git" dialog opens up, simply click add and this will add it to local file system.
14. Once code files are ready, we can commit the changes by clicking on the commit button at the end. This will open up the commit changes dialog box, in this box we can select the files we want to add the changes from, add a message and then click on the commit button at the bottom right side. 
15. Changes can also be pushed onto a remote repository, by clicking “Ctrl, Shift, K” or we can go to VCS then Git and then Push.
16. Once all is done then you would be able to see the changes pushed onto github.com. 



Definition of the terms: 
  
  GIT: Git is an open source program for tracking changes in text files. It is the core technology that GitHub, the social and user interface, is built on top of.

  GITHUB: It is an open source version control, which allows you to keep track of changes made to source codes or other documents. Multiple people can work on the same document at the same time.

  Repository: It is a directory/folder in which a project is created. The project's repository contains all of the project's files and stores each file's revision history. You can even discuss and manage your project's work within the repository.

  Clone: A clone is a copy of a repository onto your computer. A clone allows you to edit the files in your preferred editor and use Git to keep track of your changes without being online. The repository you cloned is still connected to the remote version so you can push the local changes to the remote version to keep them synced when you are online.

  Commit: A commit is a change to a file. When you make a commit to save your work, Git creates a unique ID that allows you to keep record of the specific changes commited along with who made them and when. Commits can contain a commit message which is a brief description of what changes were made.

  Push: Push is to send your committed changes to a repository on GitHub. If you change something locally, you can push those changes so that others may access them.

  Pull: Pull is when you are fetching in changes and merging them. If someone edited the remote file then you would want to pull those changes to your local computer so that it is up to date.

  Branch: A branch is a parallel version of a repository. It is made within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you make the changes you want to make, you can merge your branch back into the master branch to publish your changes.

  Merge: Merging takes the changes from one branch and applies them into another one. A merge can be done through a pull request through GitHub web interface if there are no conflicting changes, or can always be done through command line.

  Merge Conflict: A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

  Fetch: When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Fetching allows you to review changes before committing them to your local branch.

  Remote: This is the version of a repository or branch that is hosted on a server. Remote versions can be connected to local clones so that changes can be synced.


References: 
1. https://help.github.com/en/github/getting-started-with-github/github-glossary
2. https://www.jetbrains.com/community/education/#students
3. https://www.jetbrains.com/help/webstorm/using-git-integration.html
4. https://guides.github.com/activities/hello-world/
