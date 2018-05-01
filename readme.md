
Essential Topics.
- Getting some code, or creating a repo.
    - git init ;; creates a new local repo.
- Adding files.
- Checking the status.
- commiting, and good messages.
- pushing.
- pulling. (pull, fetch, clone, checkout, REBASE)
- showing.
- branching.
    - git branch <name> ;; This will create the branch
    - git checkout <name> ;; This switches to it
    - git push --set-upstream origin <name> This sets the 'upstream'. Name it correctly forfucksakes
- merging.
- patching.
- blame.
- log.
- alias.


Not Essential Topics.

- Config
    git config credential.helper ""

- Alias
    [Alias]
     lg = log --graph --pretty=format:'%Cred%h%Creset %ad %s %C(yellow)%d%Creset %C(bold blue)<%an>%Creset' --date=short
     hist = log --graph --full-history --all --pretty=format:'%Cred%h%Creset %ad %s %C(yellow)%d%Creset %C(bold blue)<%an>%Creset' --date=short
