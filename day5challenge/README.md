# Day 5 Challenge

## What do I Learn
Getting your github remotes right, as well as basic commands associated with 

`git remote`

Also learn about using the `-help` flag for different commands.

The Hope is that after this you can always pull from the original repo with `git pull origin master` and push to your fork for pull requests with git push  `<your-git-username>` master.

During the Day 2 task with remotes, I noticed that even though we got the `git remote add <username> <url>` command right, most of us had our origin pointing to the repo we forked and our <username> pointing to the original repo, that should not be the case, lets see an example. Since my Forked repo is

` https://github.com/prondubuisi/git-14days-challenge`

and the original repo is 

`https://github.com/fbdevcowerri/git-14days-challenge `

then running

 `git remote -v`

should return 
```
origin	https://github.com/fbdevcowerri/git-14days-challenge (fetch)
origin	https://github.com/fbdevcowerri/git-14days-challenge (push)
prondubuisi	https://github.com/prondubuisi/git-14days-challenge (fetch)
prondubuisi	https://github.com/prondubuisi/git-14days-challenge (push)

```

Lets assume running the `git remote -v` returns something  different for you, then we are here to fix it;

## Tasks
- Create a Github issue 

- Run different `git remote` examples from the task 

- Add Screenshot of the different `git remote` commands 

- Make commits spanning multiple lines

- Push commit to github as PR

## Day 5 Challenge, how to submit

- Create a Github issue for your commit, Issue should read `   Add screenshot for working with github remote basics for <your-name> `

- run   `   git remote -help` command, notice that the help flag shows you all possible use cases of ` git remote `

- Make Screenshot 

- run `git <any-previous-command-learnt> - help `

- Make Screenshot 

- Run `git remote add origin1 https://github.com/fbdevcowerri/git-14days-challenge` 

- Run `git remote add origin2 https://github.com/fbdevcowerri/git-14days-challenge` 

- Run `git remote add origin3 https://github.com/fbdevcowerri/git-14days-challenge`

- Run `git remote -v`

- Make screenshot 

- Run `git remote remove origin3`

- Run `git remote remove origin2`

- Run `git remote rename origin1 new-origin`

- Run `git remote set-url new-origin blahblahblah` 

- Make screenshot 

- Notice how flexible git is when you know the right commands

- Use all the knowledge gathered here to ensure that your `git remote -v` returns `origin` pointing to original repo and <your-username> pointing to your forked repo

- Make final screenshot

- Create a markdown file(<your-name-day5>.md) add all your screenshots

- Make a pull request referencing the issue you created


- Make a Post in the [Facebook group](http://bit.ly/fbowerri) telling us about your Progress and what you have learnt

- Extra -  feel free to send in a Pull request if you see a typo, spelling error anywhere in this codebase 

## Day 5 Challenge, I need help


- Google is your friend, check out Google

- See my Solution here [day4solution](day5challenge/ndubuisi-day4.md), notice that I uploaded my images on github here https://github.com/fbdevcowerri/git-14days-challenge/issues/5
- Create an issue on github and tell us what challenges you are having, someone would be kind enough to help you out
- Tell us about the challenges you are facing in the [facebook group](http://bit.ly/fbowerri)
- Wait for the solution video which comes out by the end of everyday D:, don't do this