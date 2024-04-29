# Git Assignment - AndrianaO
a. What is an issue?

It as a GitHub item in a repository where you can have discussions about some new proposals, plan your work, place your suggestions etc.
 
b. What is a pull request?

Pull request is a way to propose changes you've pushed to a branch in a repository on GitHub. It shows the difference between the content in the source branch and the content in the target, so it is easy for collaborators to discuss proposed changes and add some follow-up commits if needed. After review of your collaborators, you can merge agreed changes from one branch to another.

c. How do I open up a pull request?

In your repository go to "Pull requests" -> "New pull request" -> either click "compare and pull request" banner if it is visible (it automatically will choose the branches to compare) or click "New request" (and then choose branches to compare manually) -> click "Create pull request" and add a meaningful description 
-> Click "Create pull request" again.

d. Give me a step by step guide on how to add someone to your repository.

In your repository go to the "Settings" ->
"Access"->"Collaborators"->"Add people" -> type the person username/name/email and choose the right person -> "Add *username* to this repository"

e. What is the difference between git and GitHub?

Git is an open source version control tool that runs locally on personal computer, while GitHub is an online service built to run Git in the cloud.

f. What does git diff do?

It shows changes between two different commits or working trees (or between some other objects like blobs or files on the disk) 

g. What is the main branch?

This is the name of the default branch in GitHub. This is where the production code is stored and this version of code should always work without errors. All new features after testing should be merged with the main branch. 

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

It is better to push changes into the specified (not main) branch and create a pull request, so the proposed changes can be discussed and tested before going into the main branch. 