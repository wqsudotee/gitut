This is where we will be displaying the basic git functionality.


Essential Topics.
- Getting some code, or creating a repo.
- Adding files.
- Checking the status.
- commiting, and good messages.
- pushing.
- pulling. (pull, fetch, clone, checkout, REBASE)
- showing.
- branching.
- merging.
- patching.
- blame.
- log.
- alias.

- Config
    git config credential.helper ""

- Alias
    [Alias]
     lg = log --graph --pretty=format:'%Cred%h%Creset %ad %s %C(yellow)%d%Creset %C(bold blue)<%an>%Creset' --date=short
     hist = log --graph --full-history --all --pretty=format:'%Cred%h%Creset %ad %s %C(yellow)%d%Creset %C(bold blue)<%an>%Creset' --date=short
