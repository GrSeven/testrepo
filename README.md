# testrepo
for learning git start with looking at tutorials and documentation for git: clone, add, commit, push, pull, status and branch/checkout. 

## Please do the following:

if you haven't already go into terminal type 

git clone https://github.com/GrSeven/testrepo.git

1. Change something in the text file with your name then

git add -A

(or instead of -A you use the file path of the file you changed if you don't want to add all your changes)

git commit -m "first commit"

git push

Now your changes are on the GitHub repo. Now go into the file and edit it directly on GitHub so it is different from your local version. Then back in terminal:

git status

Should show that you are behind so you can

git pull

And it will update your local repo. If you want to see what happens when you make local changes and the master changes as well then change something locally, don't push it and then try repeat the example of changing the file directly in GitHub.

If the others in the group are changing their files, you will also see that your local repo falls behind.

