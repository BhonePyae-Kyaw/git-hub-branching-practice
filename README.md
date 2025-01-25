# Merging Concepts in Git

While taking a course, I created these notes to simplify and visualize Git branching and merging strategies. They’re designed to make these concepts easier to understand, and I’m excited to share them with you. Whether you're brushing up or learning something new, I hope you find them helpful!


### 1. Fast Forward Merge
- Fast-forward merge is quite simple - what git just has to do is to move (i.e., “fast forward”) the current branch tip up to the target branch tip. This effectively combines the histories, since all of the commits reachable from the target branch are now available through the current one.
- This results in linear path.
![Fast Forward Merge](git_notes/Fast_Forward_Merge.png)

### 2. Different History Scenario with Fast Forward Merge
- Fast-forward merge is not possible if the branches have diverged. When there is no linear path to the target branch, we can consider 2 ways.
## a. Rebase
- 
## b. 3 ways merge
![Different History Scenario](git_notes/different_history_scenerio.png)

### 3. No Fast Forward Merge

![No Fast Forward Merge](git_notes/No_FF_merge.png)

### 4. Squash Merge
![Squash Merge](git_notes/squash_merge.png)

