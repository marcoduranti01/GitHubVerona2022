# Collaborate on GitHub

How to collaborate in developing GitHub repositories?

## Scenario 1

I note that something is missing/mistaken in a repository, but I do not have the knowledge (or time) to correct it

- I create an "Issue" in a repository, signalling it to the developer(s)
- It will be up to the person in charge of the repository to address my notification and (in case) solve the problem

![issues](https://user-images.githubusercontent.com/29945305/148434990-78a2cb12-1f57-47c8-be07-00c90aa51e03.png)

## Scenario 2

I note that something is missing/mistaken in a repository, and **I do have** the knowledge (and time) to correct it

- I "fork" the repository and create a copy in my GitHub space
- I apply the changes to the repository in my GitHub space
- I send a "pull request" to the original repository
- My pull request will be reviewed and, if fine, my forked repository will be merged with the source repository

![fork](https://user-images.githubusercontent.com/29945305/148435020-5e277d02-5c6b-4d10-8d46-6a1016368def.png)

## Scenario 3

I am part of a team and I collaborate actively in the development of a repository.  
The procedure here is a bit more complex, but it is the ideal way to work on GitHub as a team.

### 3.1 Add collaborators

If I created a repository and I want to add a collaborator to contribute directly to it, I'll need to add her as contributor.
- Go to "Settings" and then "Manage access" (I will need to confirm my GitHub password - not token!!)
- Look for a collaborator by username and send an invitation (the invited collaborator will have to accept it)

![collaborate](https://user-images.githubusercontent.com/29945305/148435020-5e277d02-5c6b-4d10-8d46-6a1016368def.png)

### 3.2 Create branches

Collaborators can then modify my repository directly.  
However, it is not good practice to modify directly the "main" branch (as it can create conflicts).  
Good practice is to create alternative branches, where to work safely without the fear of "breaking" the main branch.  
Everytime you modify a file, you are asked if you want to create a new branch:  

![branch](https://user-images.githubusercontent.com/29945305/148435020-5e277d02-5c6b-4d10-8d46-6a1016368def.png)

You can also do it via command line, by modifying the command:  
`git push origin main`  
into:  
`git push origin other_branch`  

### 3.3 Send a pull request

Once you have modified the files and verified they (almost) work, you can send a pull request:  

![pull](https://user-images.githubusercontent.com/29945305/148435020-5e277d02-5c6b-4d10-8d46-6a1016368def.png)

Ideally, the pull request will have to be reviewed by the repository maintainer (or by anybody else who will be assigned to it), eventually modified to make it fully compatible, and then accepted.  

### 3.4 Example

For a nice explanation of how the process works, see [this short video](https://youtu.be/w3jLJU7DT5E)