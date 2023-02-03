## Prompt

### Git Basics
* What is Git?

  *Git is a version control system that allows collaboration, branching off a main path, and publication history of a project.*

* Why use Git? What problem does it solve?

  *Git allows developers to work alongside one another while still keeping the integrity of the history of the code
  in case a bug occurs as well as it gives them the ability to branch off of the project to work on a new feature
  of the project that is not yet ready for production.*

* What is the difference between Git and Github?

  *Git is the version control system that you use to manage the history of a project's code whereas Github is 
  more or less the interface where you can manage Git repositories through UI.*

### Git rebase

* What is Git rebase?

  *Git rebase is a git command that allows you to connect a commit to a new base commit. This would most likely
  be used if for example you had a feature branch that isn't in sync with some changes made to the main branch
  so you want to "rebase" the feature branch to the code from the main branch to make it act as if it were branched
  off of the main branch from the current version that the main branch is on instead of the version that the main
  branch was on when you last based the branch off of main.*

* What are some advantages and disadvantages of Git rebase? (At least 2 of each)

  *An advantage to git rebase is that you can make the branching of your repo more linear and have the new features/branches built off of the main branch. A disadvantage to git rebase is that you lose the ability to see minor changes that were made and therefore cannot do pull requests either.*

* When shouldn't you use Git rebase? Why?

  *You should not use git rebase on a public repo because it would replace the old commits with new ones and cause you to lose your project history.*

Create a new repo and demonstrate your knowledge of the following items with screenshots:
* A rebase merge
* An interactive rebase merge
* When you shouldn't rebase with a remote repo.

### Git reset, checkout, and revert

* What is Git reset?
* What is the difference between hard, mixed and soft?
* What is Git checkout?
* What is Git revert?
* In what ways are these commands the same and what ways are they different?
* When would you use reset, checkout, or revert? Why?

Create a new repo and demonstrate your knowledge of the following items with screenshots:

* a Git reset
* a Git checkout
* a commit
* a Git revert

### Git submodules

* What are Git submodules?
* When would you use a submodule?
* What are the advantages and disadvantages of Git submodules?
