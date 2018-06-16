# Git_Branching_Merging
This will show how we can create multiple branches and then merge to develop branch.

# Summary --
Assumption - we have two branches by default master and develop. Here develop is exact copy for master. 
In whole process we are never going to touch master branch.

...1- Login to bitbucket and go to your repo.
...2- Create your own branch (for e.g **featureBranch**) from develop branch. This we need to do in bitbucket cloud platform.
3- Now in our local we need to take a pull from develop branch. If you are not on developer branch then we can checkout any time to develop branch by-  **git checkout develop**.
4- After pull is done, then we need to switch to our newly created branch by- **git checkout featureBranch**.
5- Make your changes and then commit them. Use command like **git add .**  and **git commit -m 'commitMessage'**
6- now we need to push from feature branch. Make sure you are in featureBranch only. This can be checked by command **git status**
7- We are done. We have pushed our changes to feature branch. 
8- Merging of feature branch to develop will be taken care by one who is overall familar to whole project.


# You tube URL 

<a href="http://www.youtube.com/watch?feature=player_embedded&v=8eVbR5sftMo
" target="_blank"><img src="http://img.youtube.com/vi/8eVbR5sftMo/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
