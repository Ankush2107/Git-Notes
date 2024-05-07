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
- It is a open source.
- Widely used by developers around the world.
- Easily maintain code integrity.
- Secure.
- Flexible

### Let's start with installing git on your machine if you haven't already done so. You can download it from [here](https://git-scm.com/downloads) 

- Now after downloading git in your local computer use this command:

 ```
    git --version  
 ```

- Then create a project directory and initialize git repository in that file using this command:

```
    git init 
```
- This will create `.git` folder inside your project directory. If you want to check use `ls -a` command it will show you hidden files and folder.

#### But wait, What is Repository?
It is a folder managed by git where we can track all the changes we are making in the project.

- Now we are ready to use any git command inside this folder