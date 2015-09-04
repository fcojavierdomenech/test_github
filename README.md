# test_github
Just to test commit, clone, etc..

Firstly, I did a clone `git clone https://github.com/vivoconunxino/test_github.git` in order to get this empty repo.

*Now I'm going to modify this file and do a commit to my local repo with `git commit`. Looks like I still can't do it, from this output:
	On branch master
	Your branch is up-to-date with 'origin/master'.

	Changes not staged for commit:
	(use "git add <file>..." to update what will be committed)
	(use "git checkout -- <file>..." to discard changes in working directory)

	modified:   README.md

	no changes added to commit (use "git add" and/or "git commit -a")

But the solution is there, I'll try again but first adding the modification with `git add README.md`. Let's see the output:
	On branch master
	Your branch is up-to-date with 'origin/master'.

	Changes to be committed:
	  (use "git reset HEAD <file>..." to unstage)

		modified:   README.md

Looks like I'm ready to go. I'll commit this again and push this changes to the repo. Again I had to add the modifications before commiting and pushing with `git push origin master`

Before pushing, I want to know what has changed and what form the commits which are going to take place: `git log` gives me the modifyed, added files and the commit messages. If I want to know specifically what changes, then `git log -p` is the command I need.

