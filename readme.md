To create a DocTM repository do the following:

1) Ensure that Git is installed. Verify by typing Git in the terminal app. Following has more information on how to install Git [1]
2) Create the repository home on laptop. This will be refered as %DocTM_Home%
3) Traverse to the %DocTM_Home% using a terminal.
4) Initialize the repository inside the current folder using the command prompt.
	git init
5) Add your name and email address to the repository so that your comments and commits will be properly connected to you.
	git config --local user.name “Your name”
	git config --local user.email “Your email address”
6) Cache the github password using osxkeychain. This will simplify the login process by automating it. The link [2] gives all the necessary details.

To merge a word document, use the Tools > Merge Documents feature in MS Word. Do this with track changes enabled. Track changes can be enabled from the Review tab in MS Word. 

Document editing life cycle

Step 1. git feth to get the latest from the Repo
Step 2. Edit the document in MS Word as save the file outside the git repo
Step 3. git feth to get the latest from the Repo
Step 4. Merge the version in the git repo and the modified file and commit the file
Step 5. git pull –u origin master to load the file to the upstream


[1] http://git-scm.com/book/en/v2/Getting-Started-Installing-Git
[2] https://help.github.com/articles/caching-your-github-password-in-git/


