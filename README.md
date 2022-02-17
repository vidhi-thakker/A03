# A03 <br>
<h1>Tutorial on Git, Github and Webstorm</h1>
<h3>What is the difference between Git, Github and Webstorm?</h3>
WebStorm lets you manage Git projects hosted on GitHub directly from the IDE: clone repositories, share your projects, create forks, share code through gists, create pull requests and review incoming pull requests.
<h3>How to install Webstorm?</h3>
1. Install Webstorm using the follwing link: <a href="https://www.jetbrains.com/community/education/#students">Download Webstorm</a> <br>
2. Upon clicking the link, you would see an option to apply for a free license using your school email. Go ahead and apply for it. <br>

<h3>How to install Git?</h3>
1. Download Git using the following link: <a href="https://git-scm.com/downloads">Download Git</a> <br> 
2. Upon clikcing the link, choose your system and install the version you want. <br>
3. I installed <a href="https://brew.sh">homebrew</a>. You can do this by opening the terminal window on your system and pasting the said command on there. <br>
4. The script explains what it will do and then pauses before it does it.<br>
5. After it's done installing, it'll display "Installation successful".<br>
6. fter this, you can go ahead and paste this command on the terminal: "brew install git".<br>

<h3>Making a Github Account</h3>
1. After that's done, head to <a href="http://github.com">Github</a> and make a free account.<br>

<h3>Connecting your Github with Webstorm</h3>
1. Now go to the Webstorm System Preferences.<br>
12. Head to Version Control.<br>
13. Click on Git.<br>
14. Now enter the path to Git that your terminal displayed. <br>

<h3>Adding your Github Password to Webstorm</h3>
1. After this is done, go to Appearance and Behavior under the Webstorm System Prefernces.<br>
2.  Then head to System Settings.<br>
3.  Click on Passwords.<br>
4.  Enter your <a href="http://github.com">Github</a> password. <br>

<h3>Creating a Repository on Github</h3>
1. On <a href="http://github.com">Github</a>, Click the + sign in the upper right corner <br>
2. Choose “Create New repository” <br>
3. Make the repository public and add the readme file. <br>
4. Click Create. <br>

<h3>Creating a Repository on Webstorm</h3>
1. Select VCS. <br>
2.  Go to Import into Version Control <br>
3.   After that, go to Create Git Depositary and give it a name. <br>
4.   Click on OK.<br>

<h3>Importing a Repository from Github</h3>
1. From Main page Select Checkout from version control and then Git  OR From within Webstorm Select VCS and then Checkout from version control then Git <br>
2. Enter Github repository name. <br>
3. Enter local path name. <br>

<h3>Creating a Webstorm file</h3>
1. Now go to Files.  <br>
2. Click on New. <br>
3. Select HTMl to create your HTML file OR Select Stylesheet to create your .css file  <br>

<h3>Adding files to Git</h3>
1. The Add to Git dialog opens.<br>
2. Click Add. <br>
3. This adds to local file system.<br>

<h3>Always commit your changes</h3>
1. Make your changes and click on Commit. <br>

<h3>Push change to Remote Repository</h3>
1. Click on Ctrl + Shift + K OR go to VCS, then Git and then click on Push. <br>
2. This updates the file on Github. <br>

<h3>Github Pages</h3>

<h4>Setting up Github Pages</h4>
1. Click on Settings
2. Check the Repository name.

<h4>Choose Github Page Location</h4>
1. Select “Master branch”.<br>
2. Note the published URL. <br>

<h4>Check your GitHub Pages</h4>
1. Copy the Github.io URL into a browser. <br>
2. Post the URL into Moodle with your Github account URL. <br>

<br><br><br>

<h1>Glossary</h1>
<h4>1. Branch:</h4>A branch is an independent line of development in a project. When you create a branch (in your terminal or with the web interface), you are creating a snapshot of a certain branch, usually the main branch, at its current state. From there, you can start to make your own changes without affecting the main codebase. <br>
<h4>2. Clone:</h4>When you clone a repository, you copy the repository from GitHub.com to your local machine. Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project. <br> 
<h4>3. Commit:</h4> The git commit command will save all staged changes, along with a brief description from the user, in a “commit” to the local repository. You can think of a commit as a snapshot of your project, where a new version of that project is created in the current repository. <br>
<h4>4. Fetch:</h4> The git fetch command downloads commits, files, and refs from a remote repository into your local repo. Fetching is what you do when you want to see what everybody else has been working on.<br>
<h4>5. GIT:</h4> Git is a powerful file version control system. It gives us a history to track progress on files so that we can rewind or fast forward to a specific moment in time allowing us access to previous versions of a file. It is kind of like the best undo button you will ever learn.<br>
<h4>6. Github:</h4>GitHub is a "social coding" site. It allows you to upload code repositories for storage in the Git version control system. You can then collaborate on code projects, and the system is open-source by default, meaning that anyone in the world can find your GitHub code, use it, learn from it, and improve on it. <br>
<h4>7. Merge:</h4> It can be done by using the rowspan and colspan attribute in HTML. The rowspan is used to merge or combine the number of cells in a row whereas the colspan is used to merge column cells in a table. <br>
 <h4>8. Merge Conflict:</h4> The name gives it away: a merge conflict can occur when you integrate (or “merge”) changes from a different source into your current working branch. For example, when the exact same line of code was changed in two commits, on two different branches, Git has no way of knowing which change you prefer. <br>
<h4>9. Push:</h4> The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.<br>
<h4>10. Pull:</h4> Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch. <br>
<h4>11. Remote:</h4> A remote repository in Git, also called a remote, is a Git repository that's hosted on the Internet or another network. ... The video will take you through pushing changes to a remote repository on GitHub, viewing a remote's branches, and manually adding remote. <br>
<h4>12. Repository:</h4> In a revision control system like Git or SVN, a repo (i.e. "repository") is a place that hosts an application's code source, together with various metadata. <br>

<br><br><br>
<h2>References</h2>
1. Beer, B. (2018). Introducing GitHub. 2ed. O’Reilly Press. <br>
2. Jetbrains. (2019). Git.   Retrieved March 21, 2019, from https://www.jetbrains.com/help/webstorm/using-git-integration.html <br>
3. GitHub (2019) GitHub Guides Tutorial. Retrieved  March 19, 2019, from https://guides.github.com/activities/hello-world/ <br>
4. Atlassian. “Git Push: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing/git-push. <br>
5. 28, Tobias Günther onOct, and Tobias Günther. “Merge Conflicts: What They Are and How to Deal with Them​: CSS-Tricks.” CSS, 3 Dec. 2021, https://css-tricks.com/merge-conflicts-what-they-are-and-how-to-deal-with-them/. <br>
6. freeCodeCamp.org. “Git Commit Command Explained.” FreeCodeCamp.org, FreeCodeCamp.org, 28 Apr. 2021, https://www.freecodecamp.org/news/git-commit-command-explained/. <br>
7. “How Do I Use Github Pages? - Learn Web Development: MDN.” Learn Web Development | MDN, https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Using_Github_pages. <br>
8. “How to Create a Branch.” GitLab, https://docs.gitlab.com/ee/gitlab-basics/create-branch.html. <br>
9. “How to Merge Table Cells in HTML ?” GeeksforGeeks, 20 Dec. 2020, https://www.geeksforgeeks.org/how-to-merge-table-cells-in-html/. <br>
10. “HTML CSS Getting Started with Git.” Learn, https://learn.co/lessons/html-css-getting-started-with-git. <br>
11. “Repo - MDN Web Docs Glossary: Definitions of Web-Related Terms: MDN.” MDN Web Docs Glossary: Definitions of Web-Related Terms | MDN, https://developer.mozilla.org/en-US/docs/Glossary/Repo. <br>
12. "What Is a Git Remote?: Beginner Git Tutorial.” GitKraken, 26 May 2021, https://www.gitkraken.com/learn/git/tutorials/what-is-git-remote. <br>
13. Atlassian. “Git Fetch: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing/git-fetch. <br> 
14. “Cloning a Repository.” GitHub Docs, https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository.  <br> 
15. “About Pull Requests.” GitHub Docs, https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests. <br> 
