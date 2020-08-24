# INTRODUCTION

## Prerequisites

Before beginning this tutorial, it is highly recommended that you have a solid understanding of the Terminal (for Mac) or Command Line (for Windows and Linux).

In order to explain Git, we have to first explain various aspects of Version Control.

## Local Version Control
Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

## Centralized Version Control
The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.

## Distributed Version Control
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.

# So, what is Git?

-Snapshots

-Local Operations

-Tracking Changes

-Loss of Data

-States

![imagr](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

## Download Git

1.Install as a package

2.Install via another installer

3.Download and compile the

4.source code

# Workflow

## Local Repository Structure

The local Git repository has three components:

1.Working Directory: The actual files reside here.

2.Index: The area used for staging

3.Head: Points to the most recent commit

![i](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

#The Life Cycle of File Status

1.After you edit a file, Git flags it as modified because of changes made after the previous commit.

2.You stage the modified file.

3.Then, you commit staged 
changes.

![i](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

## Check File Status

**command**= *git status*  

## Track one file only by using the following format:

*git add filename*

## Committing a File

*git commit -m “made change x,y,z”*

## Pushing Changes

*git push origin master*

