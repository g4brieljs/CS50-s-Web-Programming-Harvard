# CS50's Web Programming Harvard

In this repository I will share my progress of the Harvard CS50's, Python and Javascript web programming course.

My name is Gabriel Jiménez, self-taught student of web development, and computer science, I am passionate about software development, I share this repository to take notes of my course.

## Table of Contents

- [Git - Version control](#git-version-control)
- [HTML and CSS](#html-and-css)
- [Git advanced](#git-advanced)
- [Flask](#flask)

## Git - Version control

- Keep track of changes to code.
- Syncrhonizes code between different people.

Git is also very good at letting you test your code without losing your original copy.

### Github

Github is just a website whose purpose in life is to store Git repositories on the internet.

- `git clone "url"`

By the url of that Github repository, that remote version of your code, will be downloaded onto your computer so that you have a copy of the repository on your own computer.

- `git init` 

- `git status`

Is a simple command that effectively just tells you what's currently going on in your repository.

If you forget whether you've made new commits since the last time you checked from Github, if you forget whether you've made new changes that you haven't committed yet, git status is an easy way to just run git status and see the current status of that's going on inside of your repository.s

- `git add .`

And the git add command basically means we're going to take some number of files, one or more files that we've changed and tell Git that these are files that we want to include the next time we make a commit, to the next time that we save we want to include the next time we make a commit, to the next time that we save a version or a snapshot of the current repository.

- `git commit -m "my first commit"`

Commit it just fancy way of saying take a snapshot of the repository in the current moment and save it.

When you run git commit dash followed by a short description of what you've done, what that'll do is have Git save a new version or a new snapshot of your repository in that moment keeping track

- `git push`

That's called a push, where we push our code from our local computer to the repository that's stored somewhere on the internet. 

And so when we run git push, that causes those changes.

Next up is sort of the inverse of that.

- `git pull`

What if someone else has been working on your repository. Has made changes to it, and pushed those to github?

And now you want to dowload the latest version of that repository.

You want to dowload the latest changes down onto your computer locally to take a look at it.

How would you go about doing that? That's by a different command called git pull.

When you run git pull, if ther eare other changes that have happened on the remote server, notice that here locally I've made on change, but someone else on Github for instance has pushed some second change that's been made to the code. 

## First project with Harvard

### Requirements 

Copy this steps becouse i need practice my write english, and sharing my progress.

Testing `git brach`

**Important** Merge Conflicts

If you make a change in your code, and the other partnert change the same file, in the master branch, you had a Merge clonflicts.  

`git log` does is effectively just show you a history of all of the commits that you've made.

`git log` in the console, you'll see a list of all the different commits that have been made.

**And then one other command that's usefl to know is** `git reset`.

## HTML and CSS 