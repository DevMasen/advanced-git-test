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
1. `git blame` : show blame configs
1. `git blame <fileName>` : for findout WHO wrote codes in a file.
1. `git blame <fileName> -L <startLine>,<endLine>` : show WHO wrote codes in a file in specific lines.
1. `git bisect start` : start debuging with git by binary search
1. `git bisect good <commitId>` : tell git that in which commit the project went good
1. `git bisect bad` : tell git in current search level project went bad
1. `git bisect good` : tell git in current search level project went good
1. `git bisect reset` : finish the search operation
1. `git tag` : show tags list
1. `git tag <tagContent>` : add a tag with \<tagContent> for last commit
1. `git tag <tagContent> <commitId>` : add a tag with \<tagContent> for commit with \<commitId>
1. `git show <tagContent>` : show changes in commit with tag \<tagContent>
1. `git tag -d <tagContent>` : delete a tag with \<tagContent>
1. `git tag -f <tagContent> <commitId>` : force set a tag for a commit
1. `git tag -l` : show tags list
1. `git tag -l '<formatString>'` : show tags through filter added by \<formatString>
1. `git checkout <tagContent>` : change head to a commit with a tag with \<tagContent>
1. `git diff <tagContent-1> <tagContent-2>` : compare changes in two commit with tags \<tagContent-1> and \<tagContent-2>
1. `git push <remote> <tagContent>` : send tag with \<tagContent> to github repo with remote \<remote> (mostly 'origin')
1. `git push <remote> --tag` : send all tags to github repo with remote \<remote> (mostly 'origin')
1. `git rebase <branchName>` : merge the \<branchName> with current branch without showing separation in branches
1. `git rebase -i HEAD~<N>` : change the last \<N> commits history
1. `git rebase --continue` : continue rebaseing after solving conflicts
1. `git rebase --abort` : cancel rebasing 