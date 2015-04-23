Go to [1] and create your account to be used with git.

To create a DocTM repository do the following:

1) Ensure that Git is installed. Verify by typing Git in the terminal app. Following has more information on how to install Git [2]

2) Create the repository home on laptop. This will be refered as %DocTM_Home%

3) Traverse to the %DocTM_Home% using a terminal.

4) Initialize the repository inside the current folder using the command prompt.

	git init

5) Add your name and email address to the repository so that your comments and commits will be properly connected to you.

	git config --local user.name “Your name”


	git config --local user.email “Your email address”


6) Clone the upstream found in git hub to your repository.

	git clone https://github.com/NalinSugathapala/wso2-training.git


To merge a word document, use the Tools > Merge Documents feature in MS Word. Do this with track changes enabled. Track changes can be enabled from the Review tab in MS Word.


Document editing life cycle

Step 1. Get the latest from the Repo

	git fetch


Step 2. Edit the document in MS Word as save the file outside the git repo

Step 3. Get the latest from the Repo

	git fetch


Step 4. Merge the version in the git repo and the modified file and commit the file

Step 5. Load the files to the upstream.

	git pull –u origin master



[1] https://github.com/

[2] http://git-scm.com/book/en/v2/Getting-Started-Installing-Git
