# Git Interview Questions

## Basics
- What is Git and how does it differ from other version control systems (e.g., SVN)?
- What is the Git index (staging area)?
- What is the difference between a working directory, staging area, and repository?
- What is the difference between a bare and non-bare repository?
- How does Git store data internally (objects, commits, trees, blobs, tags)?
- What is the difference between local and remote repositories?
- What is a commit hash (SHA-1) and how is it generated?

## Branching & Merging
- What is the difference between `git pull` and `git fetch`?
- What is the difference between `git merge` and `git rebase`?
- How does the commit tree look after merging vs rebasing?
- What is a detached HEAD in Git?
- How do you resolve conflicts during merge or rebase?
- What is fast-forward merge vs recursive merge?
- What are upstream and downstream branches?
- How do you rename or delete a branch?
- What is the difference between `git reset`, `git checkout`, and `git revert`?

## Collaboration
- How do you undo commits locally and remotely?
- How do you revert a commit that has already been pushed?
- What are Git tags and how are they used?
- What is the difference between lightweight and annotated tags?
- How do you handle multiple remotes in Git?
- How do you fetch changes from one branch and apply them to another branch?
- How can you enforce a workflow for a team (Git Flow, GitHub Flow, trunk-based development)?
- What are pull requests (PR) and how do they fit into collaboration?

## Advanced
- How do you squash commits? When would you do it?
- What is an orphan branch and how do you create one?
- How do Git hooks work? Give an example of pre-commit or post-merge hooks.
- How do you investigate the history of a file? (`git log`, `git blame`, `git bisect`)
- How do you handle large binary files in Git? (Git LFS)
- How do you perform an interactive rebase and why?
- How do you cherry-pick a commit from another branch?
- How do you create a patch file and apply it?
- How do you resolve merge conflicts in binary files?

## Best Practices
- How do you manage commit messages? What is a good commit message structure?
- How do you maintain a clean commit history in a collaborative environment?
- How do you revert a merge commit safely?
- How often should you commit changes locally?
- How do you keep your branch up-to-date with the main branch?
- How do you handle release branches and hotfixes?
- What is a Git workflow you prefer for feature development?
- How do you track bugs and changes with Git effectively?
