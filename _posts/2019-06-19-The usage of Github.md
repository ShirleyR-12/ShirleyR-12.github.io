---
layout:     post
title:      GitHub 学习记录
subtitle:   
date:       2019-06-19
author:     Shirley
header-img: img/post-bg-universe.jpg
catalog: true
tags:
    - GitHub
---

#### Respository, branch, commit, request

一般开发过程先有一些指导文档，之后会逐步开始建立一些具体的代码文件和具体记录的进展
文件。然而这些文件的最大的问题就是会被反复修改，且通常是不同人提出修改的意见。

然而存在的问题是，一方面这些修改你希望能够看到这些修改和讨论的记录，但又不想在最终过程出现这样的一些中间过程。GitHub 平台就很好的完成了这个任务，是一个great的代码**管理**平台。

* Respository：英文本意是库，可以理解通常在电脑里给一个项目专门开辟的一个文件夹，将与这个项目有关的主要文件存放的地方。

* Branch: 应该算是这个平台独特的地方。本意是树枝树杈，然后可以引申为主线和支线。Main branch is named as master, and other branches could be created when you want to make a change to original branch. Main branch可以算是provide a platform to allow主管部门,your manager or your colleges and other people to check your real progress of this project.

* Commit: The difference between original branch and new branch under development. Or regarded as saved changes.

* Request: a message to make communications between your colleagues and you when you make progress of your codes or want to discuss about questions.

#### How to use these concepts when you write codes

* When you create a project, you could create a respository. Apart from this, you could use a respository from others to create your own project, which may improve your productivity.

* When you begin your project, try to make lots of branches. Until your project is completed, let these branches merge into the main branch:master.

* Once you are in a new step of your strategy or your strategy have some changes, you could make these changes by editing them directly in the new branch you created in the Github or by uploading the file you complete it in the other platform. When you update your progress, the Github demands you commit these changes. You could write simple reasons for what you have changed and why you change them. That's, you could explain the strategy which reflects your design of your project, perhaps is about soft engineering.

* If this project is requested to show or let your colleges know about your progress, create a new branch, commit a change and use 'pull a request' to create a request. That's why the nickname of Github is 码农社交平台. By pulling a request, you even could use emoji in the description of your changes and use @ to send messages to them.

* Once you ensure the changes in your new branch could meet the criteria or be in agree with others, you could merge a pull request.

* If this project is just about yourself, create a new branch to document your everyday progress.

**Reference :**

<https://guides.github.com/activities/hello-world/>

<https://guides.github.com/introduction/flow/>

#### Github Desktop and Github

In the pratical coding situations, programmers prefer to code in their editors, such as Visual Studio Code, rather than in the Github website directly. That's, codes are wrote and stored in the PC firstly and then uploded to the website. To be convenient, Github Desktop was lauched, bridging the gap between offline and online. Programmers could focus on their codes in their laptops and Github Desktop gives almost the same platform as Github website to these developers to save changes and progress of their projects.

Advantages and Disadvantages of Github Desktop:

* could finish your project at any time and places even if you are offline
* could create, delete and rename new file or folder more efficiently than the Github web but less in cloning repositories
* could not edit codes directly but could see the changes and edit the file in other editors

Advantages and Disadvantages of Github web:

* must upload your new files and codes when the network is available
* could find a great number of creative repositories in the website and fork them into your project
* great to teamwork and social networking

这边关于Github desktop and web的东西可能需要不断发现。Github Desktop and VS code 自己也是刚刚接触。

#### Some tips

* How to create folder in the Github web?

Click 'create new file' and type the name plus '/'

**Reference:**

<https://blog.csdn.net/y_bccl27/article/details/87980986>

* How to rename your folder in the Github?

In most cases, this operation is done in the Github Desktop. And it seems that you could not rename your folder in the Github but could move your file from the current folder to a new folder by renaming your file with '..' in front of your file name. When the folder has no files, Github will delete your folder automatically.

**Reference:**

<https://segmentfault.com/q/1010000007536775?_ea=1375413>
