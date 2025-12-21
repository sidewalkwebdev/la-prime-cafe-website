# sidewalk-starter-site
template for client websites 


GIT COMMANDS - USE THESE IN THE VSCODE TERMINAL WHEN YOU WANT TO PUSH CODE 

"git pull" - this makes sure you have the newest version of the code from github

"git checkout -b my-feature" - this takes you into your own branch in order to create and test new features, you can replace the part that says my-feature with anything, for example if you're going to get started on a footer you would enter the command "git checkout -b footer"

after making a new branch, you can work on the code and when you're ready to add your new code
back to the main branch, you enter these commands:
git add .       - this is telling git to add the following changes
git commit -m "descibe what you changed here"   - this is to actually add the changes and add a message

after this, you want to push your branch to github, to do this you need to enter the command:
git push -u origin my-feature      of course, replace my-feature with whatever you named your branch

now you msut merge these changes to main, go to the repo on github, and go to "compare & pull requests", click on it and click merge pull requests. Now that the branch has been added, in the terminal in vscode you can enter the commands:
git checkout main
git pull
these commands will update your code to the latest version with the branch you just added 
