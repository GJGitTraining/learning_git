# Preliminary steps

## Install Git for Windows
Go to this link: https://gitforwindows.org/ download and install Git for Windows (keep defaults).

If you cannot install software on your machine, ask your leader to give you rights for that.

## Setup PuTTY against SAS Server
Please follow instructions here: [PuTTY setup](http://bi-portalen/Analyseplattform/AnalyseWiki/Sider/Oppsett%20av%20Putty%20mot%20server.aspx)

The only difference is that we set **Host Name (or IP address)** to: *gfsasgrid01.mistral.mistralnett.com*
Also give appropriate name under **Saved Sessions**

## Setup Windows Environment Variables (PROXY)
Please follow intructions here: [Environment Variables](http://bi-portalen/Analyseplattform/AnalyseWiki/Sider/git%20-%20connecting%20via%20proxy.aspx)

Please follow just steps in paragraph for Windows!

## Create GitHub account
Go to https://github.com/ and sign up for GitHub.

I recommend using Google Chrome (or Firefox) instead of IE.

# Course outline

This course is meant to be an introductory course to the world of `Git`. Primary audience are those who are either completely new to `Git`, never heard of it before, or just want to expand their basic knowledge of `Git`.

For those who are regularly using `Git` in their projects and will be interested, we might give a follow-up course (merging vs. rebasing, checking out, resetting, reverting, squashing, stashing, pull requests, reviews ...) if there is an interest.

## Language of instruction

This course is given in English, but feel free to ask questions in Norwegian.

## Programming language

To avoid confusion, `Git` is a version-control system (VCS), so it can be used with any programming language. Wheher you are using `C++`, `Python`, `R`, `SAS` or any other language of your preference, `Git` can help you to have control over your codebase.

We are first going to demonstrate `Git` on a simple `.txt` file. **Paul** will then guide you through the steps needed for incorporating usage of `Git` in your `SAS` projects (therefore you need to setup PuTTY first).

## Agenda

1. What is `Git`? Why do you want to (should) use it? Using `Git` for your personal projects and collaborative projects.
2. What is `GitHub` and `Bitbucket` and how they complement `Git`.
3. Little sneak peek into `TLL` and `Git`/`Bitbucket` 
4. Cloning remote repository on your machine, remote vs. local - `git clone`
5. Creating a new file and adding to staging index - `git status`, `git diff`, `git add`
6. Adding to commit history - `git commit`
7. Pushing your changes to remote repository - `git push`
8. Reading the commit log - `git log`, `GitHub`


This part of the course will be done in pairs

9. Creating own branches. Why branching and what is MASTER branch - `git checkout -b feature_branch`
10. Working on different files - `git add`, `git commit`, `git pull`, `git push`, `git branch`
11. Working on the same file - no conflict
12. Working on the same file - creating conflict and solving it.
13. Merging all branches to the MASTER - fixing conflicts

The last part will be related to the use of `Git` in connection with `SAS` projects

14. Connecting to SAS server via PuTTY
15. Saving `SAS` scripts to the file as `.sas` files.
16. Version control with `Git`
