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

### Git reset, checkout, and revert

* What is Git reset?
  *Git reset is a command which allows you to move your repository back to a previous commit thus discarding any changes made in commits after the commit you choose.*
* What is the difference between hard, mixed and soft?
   *Soft will uncommit any changes but they are left staged, mixed will uncommit and unstage any changes but they are left in working tree, and hard will uncommit, unstage, and delete any changes.*
* What is Git checkout?
   *Git checkout is a command that moves the user from the current branch to the branch specified in the checkout command line.*
* What is Git revert?
   *Git revert is a command which takes a previous commit and adds it as a new commit.*
* In what ways are these commands the same and what ways are they different?
   *Reset would be used when you want to undo any and all work that has been done since a specific commit. Checkout is used for when you want to branch off and take the code into a different direction while keeping the integrity of the original branch. Revert would be used if you wanted to revert some changes made in a previous commit (like re-adding a file that was deleted), but you don't want to lose all of the new changes made since the commit you chose for the revert.


### Git submodules

* What are Git submodules?
   *Git submodules are external repositories that the main repository depends and are linked at a specific path in the parent repository.
* When would you use a submodule?
   *Submodules are often used in complex projects. An example of a time you would use a submodule is if you wanted to use a library's source code, but you want to be able to make changes to the library's source code while also being able to keep updated with the codebase of the library.
* What are the advantages and disadvantages of Git submodules?
   *Submodules are a great way to distribute several repositiories all as one, but having submodules requires you to treat each submodule as its own separate repository thus making the parent repository much more complex to work with.
