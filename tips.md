for merging a pull request to your repo:
----------------------------------------
- Step 1: From your project repository, check out a new branch and test the changes.

	`git checkout -b MrRamoun-master master`
	`git pull https://github.com/MrRamoun/my_first_repo.git master`

- Step 2: Merge the changes and update on GitHub.

	`git checkout master`
	`git merge --no-ff MrRamoun-master`
	`git push origin master`
