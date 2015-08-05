# Setting Up on Local Machine

cd to project directory

git init			create .git repository in current directory
git remote add origin https://barnettconsulting@bitbucket.org/barnettconsulting/test.git
git status		shows status of commits
git add .			add all files recursively to staging area
git add *			add all files to staging area
git commit –m “msg”	commit staged files with a message
git log			show history of commits
git commit –am “msg”	-a stages/commits any modified/removed files
git checkout aa13		revert to a previous version
git show				shows git objects
git reflog			Show all the commits
git rm foo.html		remove file from staging area
git mv foo.html bar.html	rename file in staging area
