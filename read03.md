# **!!Revisions and the Cloud!!**
*These are my notes for Revisions and the cloud*


## **What is version control?**

Version control is a system that records changes to various files allowing you to revisit them as they once where. The Version Control System (VCS) allows you to fix any errors made to past saved code. There are 3 types of version control systems :

- **Local Version Control:**
LVCS was created many years ago and is stored on a seperate data base on your hard disk drive

- **Centralized Version Control:**
CVCS can be accessed by various clients as well as muiliple developer teams that are working on the same project.

- **Distributed Version Control:**
DVCS mirrors files or work from develper teams as copies within another drive. This helps if for any reason a file is deleted or in the case of a catastrophic loss.

## **What is Git:**

**Git is:**
- **Snapshots**
Git is a DVCS. It takes snapshots of fiels to a directory on Git each time you make a chage by commting it.
- **Tracking Changes**
Git tracks any changes made to a file.
- **Local Operations**
Git relies on local operations because most info can be found in a local resourse.
- **loss of Data**
Git can greatly reduce and reverse irreversable files that are lost.
- **States**
Files in Git can reside in three main states: Committed, Modified and Staged.
1. *(committed: Data is securely stored in a local database)*
2. *(Modified: File has been chaged but not committed to the database.)*
3. *(Staged: Flagged a file's changed version to be committed in the next snapshot.)*

## **Remote Repositories**

- **Seeing your remotes**
*Here's an example of code to see your remotes:*
<P>$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
</p>

- **Adding Remotes:**
*Here's an example of code to add Remotes:*
<p>$ git remote

origin

$ git remote add js https://github.com/janesmith/project1

$ git remote -v

origin https://github.com/johndoe/project1 (fetch)

origin https://github.com/johndoe/project1 (push)

js     https://github.com/janesmith/project1 (fetch)

js     https://github.com/janesmith/project1 (push)
</p>

*These are just some examples.*





















[<==back](README.md)
