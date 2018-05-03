Things you do each day.
- Doing
    - Create/pull a repo
        - git init
        - git clone

    - Getting (or switching) a branch,
        - git checkout <branch> 

    - Making a branch,
        - git branch <name>

    - making changes,
        - git add
        - git commit
            - Get messages right.
            - Don't amend published commits.
        - git push

    - getting changes
        - git pull

    - merging back,
        - git merge

- Undoing
    - revert (undo a commit with opposing changes)
    - reset (bye bye all staged changes)
        - git reset ;; undo staged
        - git checkout * ;; undo unstaged
        - git reset --hard ;; Don't reset on a branch that has never been pushed.
        - git rm --cached file 
        - git reset --merge ;; reverts the merged stuff
    - checkout (bye bye changes 1 file)

- Reading
    - status
        - git status
        - git status -vv
        - git show
        - git log -1 -p ;; diff of last commit.
        - git diff ;; Unstaged diff
        - git diff --cached staged diff
    - looking at branches/branching
        - git branch -av
        - git checkout <branch>
    - blaming
        - git blame <file>
    - diffing between two revisions.

Things you do less often.
- rebasing.
- cherrypicking.
- stashing.
- git config credential.helper ""

Alias
[Alias]
     lg = log --graph --pretty=format:'%Cred%h%Creset %ad %s %C(yellow)%d%Creset %C(bold blue)<%an>%Creset' --date=short
     hist = log --graph --full-history --all --pretty=format:'%Cred%h%Creset %ad %s %C(yellow)%d%Creset %C(bold blue)<%an>%Creset' --date=short
