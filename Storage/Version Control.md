Materials:
- Git (Installed)
- Github (Installed)
- Github account
- Obsidian

Author notes:
I would suggest using github desktop for doing git work if you have no git experience, though command line is preferred.

---
## Vocab
- Git is the version control system
- Github is the website that git sends too
- Repo/Repository is where all of the content is storage for remote access
- Snapshot is a commit that is commited change to a local repository already
- Branches are the current working versions of the repository
- HEAD is the pointer for your local repository, pointing to the working branch and tree that you have checked out
- Checkout is the action when changing your head to a branch

## Branches in a [nutshell](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) inside of a nutshell:
In practice:
- HEAD points to which branch you are currently working on if you have multiple, HEADs are local.
- Branches are attached to the most recent snapshot (version saved to github).
![[Branches_1.svg]]
- The HEAD branch you are on moves forward when commited, any other branch is left on the last commit it was commited with.
![[Branches_2.svg]]
- Changing your head again will move the head back to the <u> Test </u> branch, and revert the changes in your working directory to the ones contained on that snapshot.
- Commiting, after moving your HEAD from <u> Main </u> to <u> Test </u>, at this point will cause divergent changes, and split your snapshots into 2 seperate branches which will need to be merged later.
![[Branches_3.svg]]

## Command line (Windows)

To view documentation

`git -h`

or

`git <command> -h`

To simply commit with a message:

`git commit -m "commit message"`

To pull latest updates:

`git pull origin/<branch name>`