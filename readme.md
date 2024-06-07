# Version Control System

It is a tool to manage version and changes in a software.
Version means particular state of a software.

for eg: Enhancement, adding features, and removing bugs etc.

## How Version Control System helps us ?
- Helps us to track changes.
- Manage versions and their rollbacks.
- Compare changes in versions.
- Log the changes.
- Collaboration.

## Few version control system 
- Mercurial
- Git
etc...

## In this session we will be using Git as our version control system.
- It is open source.
- Widely used by developers around the world.
- Easily maintain code integrity.
- Secure.
- Flexible

### Let's start with installing git on your machine if you haven't already done so. You can download it from [here](https://git-scm.com/downloads) 

- Now after downloading git in your local computer use this command:

 ```
    git --version  
 ```

 - Configure your Git username and email using the following commands

 ```
    git config --global user.name "Your name"
    git config --global user.email "Your email"
 ```

- Then create a project directory and initialize git repository in that file using this command:

```
    git init 
```
It intializes your git repository

- This will create `.git` folder inside your project directory. If you want to check use `ls -a` command it will show you hidden files and folder.

#### But wait, What is Repository?
It is a folder managed by git where we can track all the changes we are making in the project.

- Now we are ready to use any git command inside this folder, but before using any other command create a new project, intialize git in that project and write some code: 

`script.js`

```
    console.log("Hello World");
```

then use the command below:

```
    git status
```

In the world of git a new version is mentioned as a new commit. If we have to create a new a new versiion we have to create a new commit.

### What is untracked file?

Git not automatically find what file or what folder will going to add in the new version, You need to manually tell git that this are thefiles, I need to add in the new version, Now how we can tell git to add this files in the version, by using the command below:

```
    git add script.js
```
Whatever are the files your want to start tracking this command will help you for that task.