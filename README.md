# A03


Github is an open source version control system. Version control is the use of a system to keep track of changes to source code or other documents.
Multiple people can work on the same repository at the same time, and if a serious, unsolvable bug is introduced in a new version, one can always revert back to a previous verison.
Github is free, displays differences between versions, as well as allowing for people who add code to write out their changes and other documentation they feel is necessary.
Github has an online version and a local version, so that one does not need to constantly upload their code to the online repository until they deem it necessary.
Gitbash is a unix based program made to operate on Windows environments to provide the same utilities that linux has for pushing and pulling repositories between local and online.

Webstorm is an IDE managed by jetbrains that is used for coding javascript and it's related technologies. Webstorm, being apart of jetbrains, also has github support in order to connect your account and manage repositories directly through the Webstorm user interface.

In order to use github:

First: Download [Webstorm](https://www.jetbrains.com/webstorm/download/#section=windows) and [Gitbash](https://git-scm.com/downloads)

Second: Set up an account on github, then click create a repository

![image](https://user-images.githubusercontent.com/47003644/193946730-2874a17d-5b62-41fe-800b-d7644c679305.png)

![image](https://user-images.githubusercontent.com/47003644/193946818-1b4c95b8-69bf-410b-944e-accf103083ff.png)

After naming it and creating it, move to your downloaded Webstorm and go to projects and select "Get from VCS"

![image](https://user-images.githubusercontent.com/47003644/193948248-5cf4757c-5240-4786-8f7c-4c6141dbd920.png)

It'll promt for a github account login, just use the "Login with github account", as long as you are logged into github in your browser, it should be able to connect.

![image](https://user-images.githubusercontent.com/47003644/193948422-e78ee0d8-df8f-4146-9a8e-f08d505b9e2b.png)

Afterwards, you should be able to view ALL the repositories you are able to access, select the one you just made, and hit clone.

![image](https://user-images.githubusercontent.com/47003644/193948493-e5970567-133c-4338-b828-5ab5f8a40475.png)

Congrats! You now have a version of your repository on your local computer!
(make sure to hit trust project)

Afterwards, we want to be able to create and upload files to our remote repository in git hub, so let's create a test file

Right click the folder > new file > HTML

![image](https://user-images.githubusercontent.com/47003644/193948697-8cf457cc-560c-4c74-81fe-15ecded694ec.png)

Name it 'test', and hit add to git when the pop up asks you to add it.

Now to commit, go to git > commit

![image](https://user-images.githubusercontent.com/47003644/193948767-97adfc7c-5c99-4b0e-90c7-0a5c36a4ecfc.png)

A text box will appear in the bottom left, write some notes on what this version of your code does. For example: "Added the HTML file test, created a local branch"

Then hit commit and push, if the instructions were followed, you should be able to see your updated code on the github repository.

![image](https://user-images.githubusercontent.com/47003644/193948883-8d244d88-fb78-42f0-b0a2-ff0c8ba69c23.png)


![image](https://user-images.githubusercontent.com/47003644/193948919-7a80e8cd-a8e6-4b3d-80b5-c83f3a092a25.png)

Success!


Glossary:

Branch - a separate branch of the main repository to safely edit and test code without possibly affected the main branch

Clone - taking an existing repository and make a clone of it in a new repository, or in a new location. Effectively a copy paste, so to speak.

Commit - captures a snapshot of the currently staged changes, where git looks at your modified projects and lists all the changes you've made. You can also add a message(highly reccomended) to describe what you attempted to do with these changes.

Fetch - a command used in Gitbash, Download objects and refs from another repository

GIT - free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Github - for-profit company that offers a cloud-based Git repository hosting service. Without github, using git would be much more difficult to set up, as you would have to provide your own hosting to store a repository.

Merge - command used in gitbash - Join two or more development histories together. This command is used by git pull to incorporate changes from another repository and can be used by hand to merge changes from one branch into another.

Merge Conflict - an issue that git ran into when attempting to do a merge. These occur when it is an unsolveable issue, such as one developer deleting a file that another was working on, or another editing a line such that another developer's would make no sense.

Push - command used in gitbash - used to upload local repository content to a remote repository.

Pull - command used in gitbash - used to fetch and download content from a remote repository and immediately update the local repository to match that content

Remote - meaning online.

Repository - a repository in git context contain a collections of files of various different versions of a Project

Sources used:

https://www.jetbrains.com/help/webstorm/meet-webstorm.html

https://njit.instructure.com/courses/24638/files/3881219?module_item_id=872572

https://docs.github.com/en

https://git-scm.com/doc
