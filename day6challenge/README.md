# Day 6 Challenge

## What do I Learn
Drum roll, lets talk about branches. The git branch workflow is a way to keep things sane, I am sure we have been having lots of pull/push/merge conflicts. Conflicts within Git repositories can be better managed through git branches.

Usually there is a master branch, that only pulls in changes from `origin master` and serves as a basis for breaking out to other branches for fixing issues, making contributions and untimately making pull requests. Lets paint a picture, When you clone a repo, you have a `master` branch, then you want to fix an issue with the footer of an imaginary `footer` website you are working on. Following the branching workflow, you will create a branch for this by running `git branch fix-website-footer-button` notice that the branch is named in such a way that you understand the fix we are going to introduce using the branch. to go to our new branch we run `git checkout fix-website-footer-button` make changes on the branch(no worries you vscode will respond accordingly). After the changes we can then push to our forked repo by running `git push <github-name> <branchname>` for me I would run `git push prondubuisi fix-website-footer-button` this approach offers us lots of benefits

* Your master branch is always at the same point as `origin master`
* With branches you can make multiple pull request(Yay!) you just have to create a branch, checkout to the branch and make pushes to your forked remote
* Making pushes to a branch automatically shows you an option for pull requests
* You can work on multiple tasks at the same time
* You can remain sane!

## Tasks
- Create a Github issue 

- Create 3 branches namely `add-gitbranch-first-screenshot` `add-gitbranch-second-screenshot` and `delete-branch`

- Add Screenshot for the different `git branch` commands 

- Make commits spanning multiple lines

- Push commit to github as PR

## Day 6 Challenge, how to submit

- make sure your commits are in sync with origin, `run git pull origin master`

- run `git branch`

- Make sure you are in the master branch

- If you are not you can run `git checkout master`


- Create three new branches from `master` branch branches should be named `add-gitbranch-first-screenshot` `add-gitbranch-second-screenshot` and `delete-branch`

- Add Screenshot to show output of above commands

- Delete the last branch with `git branch -d delete-branch` 

- Run `git branch -help` to see possible commands

- Run `git branch` to see remaining branches

- Make Screenshot to show  output for above commands 

- go to First branch with `git checkout add-gitbranch-first-screenshot`

- create a file in `day6challenge` folder called `yourname-day6-branch1.md`

- add first screenshot to the readme file created,

- Add and commit changes, push branch to your forked repo using `git push <your-name > add-gitbranch-first-screenshot`

- Make a pull request with the pushed branch

- Now checkout to the second branch with `git checkout add-gitbranch-second-screenshot`

 create a file in `day6challenge` folder called `yourname-day6-branch2.md`

- add second screenshot to the readme file created,

- Add and commit changes, push branch to your forked repo using `git push <your-name > add-gitbranch-second-screenshot`

- Make a pull request with the pushed branch

- Notice that you are able to make mutliple pull requests using the branch workflow




- Make a Post in the [Facebook group](http://bit.ly/fbowerri) telling us about your Progress and what you have learnt

- Extra -  feel free to send in a Pull request if you see a typo, spelling error anywhere in this codebase 

## Day 6 Challenge, I need help


- Google is your friend, check out Google

- See my Solution here [day6solution](day6challenge/), notice that I uploaded my images on github here https://github.com/fbdevcowerri/git-14days-challenge/issues/85
- Create an issue on github and tell us what challenges you are having, someone would be kind enough to help you out
- Tell us about the challenges you are facing in the [facebook group](http://bit.ly/fbowerri)
- Wait for the solution video which comes out by the end of everyday D:, don't do this