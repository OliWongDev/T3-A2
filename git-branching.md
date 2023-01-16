## Setup

1. 'git clone' the repo at the desired folder point

```git clone git@github.com:OliWongDev/T3-A2.git```



## Making a git branch
- Make a git branch so that you can work on certain code edits without conflicting with what is going on with the master branch.


1. Make a branch

```git branch "mybranch"```



2. Select into the branch you want to begin making changes on, probably the one you just made.

```git checkout "mybranch"```



(Make the changes)




3. Add and commit the changes onto your branch

```git add .```

```git commit -m "branch commit"```

(NOTE: The changes here have not been merged to the master code yet. This is just saving to your branch you are working on.)



4. Push the commits of your branch

```git push origin "mybranch"```

(NOTE: Once pushed, your branch with the latest commits should be visible on github.)

5. Raise a pull request on github.

This might also be called a merge request (preparing to merge our branch to the main code). This is essentially 'nominating' your branch to be merged with the main code for someone else to approve (I think haha).

```github.com/OliWongDev/T3-A2/pulls```

Create a new pull request on github to request a merge of your feature branch to the main code.


6. Pull request will be merged.

(Unsure at this stage if it's me who needs to do that when they come in.)


7. Pull the merged changes into your local main so that you're working from the new changes.

```git checkout main```

```git pull origin main```


8. Delete your feature branch

(NOTE: If this feature branch is completed e.g the feature we developed is complete and merged successfully, we can delete the feature branch so that it doesn't clutter up the code.

If we need to edit this feature later on, we can just make a new branch)

```git branch -d "mybranch"```


9. Check Github to see if it's all working.