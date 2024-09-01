## Commands : 
1. `git commit --amend` : for changing the last commit with new codes in WD
1. `git stash` : save codes in WD
1. `git stash save <message>` : save codes in WD with a *\<message>* 
1. `git stash list` : show the stash list in a branch
1. `git stash pop [stash@{<stashId>}]` : take back the last stash to WD and delete the stash
1. `git stash show [stash@{<stashId>}]` : show the last stash changes
\<stashId>
1. `git stash show -p stash@{<stashId>}` : show the detailed changes in a stash
1. `git stash apply [stash@{<stashId>}]` : take back the last stash to WD without delete the stash
1. `git stash drop stash@{<stashId>}` : delete a stash
1. `git stash clear` : delete all stash list 