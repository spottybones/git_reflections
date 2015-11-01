## When would you want to use a remote repository rather than keeping all your work local?

There are several reasons to use a remote repository:
 1. to maintain a backup of your local repository
 2. to be able to clone to and work on its contents from different machines (remember to push changes back!)
 3. to collaborate with others by providing a source of the repository and a method to merge in their changes

## Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?

So you stay focused on your current work without being distracted by new cide
coming in from the repository.

## Describe the differences between forks, clones, and branches. When would you
## use one instead of another?

A Fork is a clone of a repository hosted on Github made on Github. A clone is a
copy of another repository (which may reside on Github) to a non-Github hosted
repository. A branch is a separate line of development, or a branch off a
previous commit, within a repository.

Use a **Fork** if you want to clone another's repository on Github to your own
remote on Github. Use a **Clone** if either repository is not stored on Github.
Use a branch for work inside a single repository.

## What is the benefit of having a copy of the last known state of the remote
## stored locally?

You can compare and merge changes from the last known state of the remote with
your local branches without having to be online.

## How would you collaborate without using Git or GitHub? What would be easier,
## and what would be harder?

I'd use a different version control system, probably one that retains a central
repository. These can be simpler (perhaps not easier) to work with because
there's only one copy of the repository. They can be more difficult to work with
because they don't have the same collaboration features that Git and Github do.
