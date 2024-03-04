# git_survival_guide
## Cloning:
<code>git clone https://github.com/user/repo </code>

To work in a git repository you need first to clone it. Clone operation allow you to have a copy of repository in local.

## Fetching:
<code>git fetch</code>

Fetch update pointers and download commits that you do not have in local and are present in repository **BUT** it does not changes your local files.

## Pulling:
<code>git pull</code>

Pull join your local files with files downloaded from repository.

**BEFORE PUSH YOU MUST PULL A L W A Y S**

## Committing:
<code>git add *file or directory you want to add to the commit*</code>

<code>git add .</code>

<code>git commit -m "*message*"</code>  

To commit you need to **add** file or directory to the next commit, then you must write your changes in the **message**

## Branching:
Create a new branch: <code>git branch *branch name*</code> 

Select a branch: <code>git checkout *branch name*</code>

## Pushing:

## Merging:

<code>git merge *branch name*</code>

Merge allow you to fuse two different branches **CHECK FOR CONFLICTS**

## Rebasing:

<code>git rebase *branch name*</code>

Rebase allow you to move your actual branch into *branch name* as a new commit
