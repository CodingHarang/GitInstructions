#### git init
> create local repository
#### git status [-s]
> check status of current local branch
> -s : show brief status
#### git add \<file | directory\>
> add file or directory to stage
#### git rm --cached \<file | directory\>
> remove file or directory from cache
#### git commit [-m "commit message"]
> group modifications into commit and make brief commit message
#### git commit -v
> open commit message vi containing git diff and commit
#### git diff [HEAD]
> show modifications between last commit and current code
#### git diff [\<branch1\>] \<branch2\>
> show difference between branch1 and branch2
#### git diff [\<commit1\>] \<commit2\>
> show difference between commit1 and commit2
#### git tag \<tag\> [-a [-m]]
> add tag to last commit
> -a : Annotated tag
> -m : create message
#### git tag \<tag\> \<commit\>
> add tag to specified commit
#### git tag
> show tag list
#### git show \<tag\>
> show detailed description of specified tag
#### git remote add origin \<remote repo address\>
> connect local branch to remote branch
#### git clone \< remote repo address\>
> bring copy of remote repository to local -> local repository is created
#### git log [--oneline]
> show commit log of current branch
> --oneline : show one brief line
#### git log origin/master..[HEAD]
> show commit that is in HEAD and not in remote repository
#### git log --graph
> show commit log as graph
#### git branch [--list | -r -a]
> check branch list of local/remote/all
#### git checkout [-b] \<branch\>
> move to selected branch
> b : make and move
#### git branch -d[-D] \<branch\>
> delete selected branch
> -D : forced deletion
#### git push -d origin \<branch\>
> delete remote branch
#### git fetch
> update remote branch list
#### git merge \<branch\>
> bring modification of current branch
#### git merge \<branch1\> \<branch2\>
> bring change of branch2 to branch1 
