- `git init`: initialise current folder as a git repository
- `git clone <URL>`: brings the git repo from <URL> to current folder
- `git status`: tells us what we need to know about repository

- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: open a text editor to write commit messages
    - `git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor

- `git log`: shows the log (history) of our commits
    - `git log --oneline`: shos the shorter oneline commit

- `git diff`: compare current uncommitted state with last known git state
    - `git diff --staged`: runs git diff between the staging area and last known state

- `git diff HEAD~<NUMBER>`: compares HEAD with commit <NUMBER> ago (relative)
- `git diff <HASH>`: compares HEAD with the commit in <HASH>

