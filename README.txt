1. `git init` -> Powers your folder to be managed by git, and initialises a new empty repository.
It also .git folder that has all the relevant logic to manage versions of your project.

2. `rm -rf .git`  ->  To get rid og git from the repository, when .git folder gets deleted,
our repository is no longer managed by git.

3. `working area` -> There can be a bunch of files that are not currently handeled by git.
It means changes done or to be done in those files are not managed by git yet. A file 
which is in working area is considered to be not in the staging area. When we do `git status`
we see a bunch of `untracked files` then these are actually called to be in the working area.

3. `Staging area` -> What all files are going to be part of the next version that we will create.
This staging area is the place where git knows what changes will be done from the last version to
the next version. 

4. `Repository area` -> This area actually contains the details of all your previous registered 
version. And the files in this area, git already manages them and knows there version history.

5. `git add <file>` -> Moves file from working area to staging area.

6. `git rm --cached <file>` -> Moves file back from staging area to working area.

7. `commit` -> Commit is the particular version of the project. It captures a snapshot of the project's 
stage changes and creates a version out of it.

8. `git commit` -> registers staging changes to a commit.
