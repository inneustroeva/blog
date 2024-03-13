---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Git"
subtitle: "Version control Git"
summary: "Version control Git"
authors: [Irina Neustroeva]
tags: []
categories: []
date: 2024-03-14T01:02:14+03:00
lastmod: 2024-03-14T01:02:14+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

# "Version control Git"

The version control system tracks the history of changes in the process of collaboration on projects. 
As developers make changes to the project, you can restore any earlier version of it at any time.

Developers can view the project log to find out the following:

- what changes have been made;
- who made the changes;
- what changes have been made;
- why the changes were needed.

A GIT repository or project includes a complete set of files and folders associated with the project, as well as a change log of each file. 
The file log is presented as snapshots at specific points in time. These snapshots are called fixations. 
Commits can be organized along several lines of development, called branches. 
Since GIT is a distributed version control system, repositories are autonomous units and any user who has a copy of the repository can access the entire code base and its history. U
sing the command line or other convenient interfaces, the following actions are also possible with the GIT repository: 
interacting with the log, cloning the repository, creating branches, committing, merging, comparing changes in different versions of the code, and much more.

When working with GIT, developers use specific commands to copy, create, modify, and merge code. 
These commands can be executed directly from the command line or using an application such as GitHub Desktop. 
Below are some common commands for working with GIT.

git init — initializes a new GIT repository and starts tracking the existing directory. 
A hidden subfolder is added to the existing directory, which houses the internal data structure needed for version control.

git clone — creates a local copy of a project that already exists remotely. 
The clone includes all project files, log and branches.

git add — prepares the change. GIT tracks changes in the developer's code base

git commit — saves a snapshot in the project log and completes the change tracking process.

git status — выводит состояние изменений: не отслеживаются, изменены или подготовлены.

git branch — показывает ветви, с которыми ведется локальная работа.

git merge — выполняет слияние линий разработки. Эта команда обычно применяется для объединения изменений, внесенных в двух разных ветвях

git push — обновляет удаленный репозиторий с учетом фиксаций, выполненных в ветви локально.

There are two main ways to collaborate on GitHub:

1. shared repository;
2. creating forks and pulling.

In the case of a shared repository, individual users and teams are explicitly assigned by participants with read, write, or administrative access. T
his simple permission structure, combined with features such as protected branches, helps teams get started quickly after implementing GitHub.

For open source projects or projects in which any user can participate, managing individual permissions can be a daunting task. In this case, a fork-and-pull model is more convenient, which allows everyone who can view the project to participate in it. A fork is a copy of the project in the developer's personal account. Each developer has full control over the fork and is free to implement a fix or a new feature. The results of work in forks are either stored separately or transferred back to the original project using a pull request.










