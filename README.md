# Repository of WoCCode Badges

Hello world! We are using this repository as a basecamp for practicing Github open source contribution workflows and coding. You can earn badges by opening pull requests to this repository.

| Name | Github handle | Badge repo | Badges earned |
|------|---------------|------------|---------------|
| -- | --  | -- | ![Completed WoCCode Github Level 1](https://img.shields.io/badge/woccode-Github_101-purple) |

## Github Level 101

 ![Completed WoCCode Github Level 1](https://img.shields.io/badge/woccode-Github_Level_1-purple) 

You are not required to complete the Github Mastery activities in order complete other modules in this repo. However, you will need to be comfortable forking, opening pull requests, and synching your fork with this repository. These skills are covered by the first two Github activities.

To get started, you will need to:

* Have a Github account. If you don't have one, you can [create a Github account](https://github.com/) for free

* Make sure that you have [git installed on your computer](https://github.com/git-guides/install-git)

* Get comfortable with navigating your computer from the command line. [Here's an example of a free crash course on using the command line, on YouTube](https://www.youtube.com/watch?v=uwAqEzhyjtw)

* HIGHLY RECOMMENDED BEFORE YOU START: [Set up an ssh-key or cache your user credentials](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git#authenticating-with-github-from-git) to ease your access to Github

* If you need help with terminology, see the [Github glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary)

### Part 1

1. Fork this repository and clone your fork to your computer. See the ["Forking a Repository" instructions on this page](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).
2. Create and checkout a new branch. I recommend doing this [from the command line](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging):
```
git branch github-level1
git checkout github-level1
```
3. Edit this document to add your name, Github handle, and link to your forked badges repo in the table above
4. Submit a pull request to this repo. [See this documentation for creating pull requests on Github.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

### Part 2

To complete this activity, you need to wait for your pull request from Activity 1 to be merged. The "Level 101" badge will not be displayed on your own fork until you complete the following tasks.

1. Add the woccode/woccode-badges repo as a remote repo on your local computer repository.

> **_TIP:_** It is a common practice to use the alias "upstream" for the location of the original repo. This can be done by running
>
> `git remote add upstream git@github.com:woccode/woccode-badges.git`
>
> or
>
> `git remote add upstream https://github.com/woccode/woccode-badges.git`
>
> depending on which authentication protocol you are using.

[Click here for more general documentation about managing remote repositories.](https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories)

2. Sync the `main` branch on your local computer repo to match the `main` branch of the upstream repo by running
```
git checkout main
git pull upstream main
```

4. Bring your fork on Github up-to-date by pushing the `main` branch from you local computer to the `origin` repo by running
```
git push origin main
```

## Python Fundamentals and Github Code Review

Coming soon!
