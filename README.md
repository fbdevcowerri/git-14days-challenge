# git-14days-challenge
Get(Git) up and running with Git, by following through on our 14 Days Git/Github Mastery Challenge

* [Day 1 Challenge](/README.md#day-1-challenge)
* [Day 2 Challenge](/README.md#day-2-challenge)
* [Day 3 Challenge](/README.md#day-3-challenge)

# Day 1 Challenge

## What do I Learn

How to create a Github account, fork and clone repos as well as work with .md files

## Tasks

- Create a Github Account

- Create a Github repo

- Clone the repo you just created to your System

- Fork An already existing repo

- Clone forked repo to your System

Extra -  feel free to send in a Pull request if you see a typo, spelling error anywhere in this codebase 

## Day 1 Challenge, how to submit
- Create a file called `<yourname-day1.md>` in the [day1challenge](day1challenge) folder

- Add a Screenshot image of your github repo

- Add a Screenshot image of your forked github repo

- Add a Screenshot image of any of your forked repositories , which you have cloned locally

- Make a pull request to submit your file

- Make a Post in the [Facebook group](http://bit.ly/fbowerri) telling us about your Progress and what you have learnt

## Day 1 Challenge, I need help
- Google is your friend, check out Google
- Watch this Video by the Facebook Open Source Team https://youtu.be/c6b6B9oN4Vg
- See my Solution here [day1solution](day1challenge/ndubuisi-day1.md), notice that I uploaded my images on github here https://github.com/fbdevcowerri/git-14days-challenge/issues/5
- Create an issue on github and tell us what challenges you are having, someone would be kind enough to help you out
- Tell us about the challenges you are facing in the [facebook group](http://bit.ly/fbowerri)
- Wait for the solution video which comes out by the end of everyday D:, don't do this



# Day 2 Challenge

## What do I Learn

Learn about Git remotes. Github repositories are capable of having different remotes(URL pointers), usually one pointing to the original repository and one pointing to the forked repository. Changes on the original repository are pulled(git pull) to make the local code base up to date. When the local codebase is up to date, additional code can be added to it, then a push is made to the forked repository to make it up to date or ready for pull requests. That said a typical Git/Github project involves the Original repository(origin), the forked repository(free to call it what you want), and a local copy.

## Tasks

- Add Multiple remotes to your project

- One remote should be called origin(The Original Repository), that is https://github.com/fbdevcowerri/git-14days-challenge

- The Other remote should be called <your-github-name>, i.e prondubuisi, in my case that is https://github.com/prondubuisi/git-14days-challenge

- Pull from  remote origin to keep local repo up to date

- Push to  forked <your-github-name> repo to keep forked repo up to date

- Add Screenshots to show command execution

Extra -  feel free to send in a Pull request if you see a typo, spelling error anywhere in this codebase 

## Day 2 Challenge, how to submit
- Create a file called <yourname-day2.md> in the [day2challenge](day2challenge) folder, for screenshots

- To see all your current remotes

- Run `git remote -v` on terminal or CMD

- Add Screenshot to show output

- Add a new remote with format `git remote add <github-name> <your-forked-repo-url>` 

- In my case I will Run `git remote add prondubuisi https://github.com/prondubuisi/git-14days-challenge`

- Run `git remote -v` on terminal or CMD to see new remotes

- Add screenshot to show output

- To pull changes from Original repository

- run `git pull origin master`

- To push changes to forked repository

- run `git push <git-username> master`

- In my case I will run `git push prondubuisi master`

- add Screenshot to show command output

- Add all screenshots to file created and make a pull request

- Make a Post in the [Facebook group](http://bit.ly/fbowerri) telling us about your Progress and what you have learnt

## Day 2 Challenge, 2 need help
- Google is your friend, check out Google
- Watch this Video by the Facebook Open Source Team https://youtu.be/c6b6B9oN4Vg
- See my Solution here [day2solution](day2challenge/ndubuisi-day2.md), notice that I uploaded my images on github here https://github.com/fbdevcowerri/git-14days-challenge/issues/5
- Create an issue on github and tell us what challenges you are having, someone would be kind enough to help you out
- Tell us about the challenges you are facing in the [facebook group](http://bit.ly/fbowerri)
- Wait for the solution video which comes out by the end of everyday D:, don't do this

# Day 3 Challenge

## What do I Learn
We will master creating github issues, making issues reference commits , writing good commit messages and
writing commits that span multiple lines. We will also learn about git log and 
git status commands.

Writing good and clear commit messages is one of the recommended git best practices.

## Tasks
- Create Github issue for your commit

- Make commits spanning multiple lines

- Write good commit messages

- Push commit to github as PR

## Day 3 Challenge, how to submit
- Create an Issue on this repository. Issue should read Add `<my-name>` to contributors list
  
- In my case it will read Add Ndubuisi Onyemenam to Contributors list

- Go to Project folder in your computer and Run the `git log` command on your CMD or Terminal

- You will see a blinking colon :, type wq then enter to exit

- Run `git status` command on your CMD or Terminal

- Add screenshot to show both output

- Run git pull origin master to pull in lastest changes from repo

- Add your name to [contributors.md](day3challenge/contributors.md)  file in day3challenge folder

- run `git add .` to add all changes

- run `git commit` command without the -m flag

- Notice that you have a text editor open

- Screenshot the open Editor

- Write Commit message header i.e Add my name to contributors list

- add screenshot of commands made

- Write Fixes Issue #`<the issue number you created>` above in the line following it
 - All in all your commit message will look like
  ```
  Add my name to contributors list
  
  add screenshot of commands made
  fix issue #27
  
  ```
- Pro Tip: All commit messages should  be in the present tense

- Also good commit message are in the format ; this commit will "Your commit message in present tense", all our commit messges fit well with this rule i.e this commit will;  fix issue #27 etc
  
- Since commit messages should not be more than 50 characters long(too), we write extra commit message lines  after the initial message line, see [screenshot](day3challenge/ndubuisi-day3.md#add-editor-screenshot) for example

- Save file by pressing Controlkey + o

- Then press enter

- Press Control + x to exit the editor

- Create a file called <yourname-day3.md> in the [day3challenge](day3challenge) folder

- Add a Screenshot image for git status and git log command

- Add a Screenshot image for the git commit editor 

- Make a pull request to submit contributors.md file and your day 3 screenshot file

- Make a Post in the [Facebook group](http://bit.ly/fbowerri) telling us about your Progress and what you have learnt

- Extra -  feel free to send in a Pull request if you see a typo, spelling error anywhere in this codebase 

## Day 3 Challenge, I need help
- Read this wonderful post on commit messages https://medium.com/@steveamaza/how-to-write-a-proper-git-commit-message-e028865e5791
- You can also read this too https://chris.beams.io/posts/git-commit/
- Google is your friend, check out Google
- Watch this Video by the Facebook Open Source Team https://youtu.be/c6b6B9oN4Vg
- See my Solution here [day1solution](day1challenge/ndubuisi-day1.md), notice that I uploaded my images on github here https://github.com/fbdevcowerri/git-14days-challenge/issues/5
- Create an issue on github and tell us what challenges you are having, someone would be kind enough to help you out
- Tell us about the challenges you are facing in the [facebook group](http://bit.ly/fbowerri)
- Wait for the solution video which comes out by the end of everyday D:, don't do this

