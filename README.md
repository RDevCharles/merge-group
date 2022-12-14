# Merge Group

This is a guided exercise for a pair of students to work through together. It
will walk you through resolving merge conflicts. You will have to follow each
step exactly and in order.

With your pair, decide who will play the role of Student 1 and Student 2!

## Setting up the Repository

**Git Managaer**

- Create a new repository on GitHub named "merge-test". Don't select
  the "Initialize this repository with a README" option on GitHub!
- Add the other emgineers as collaborators to your repo by going to the Settings
  tab then selecting "Collaborators & Teams" on the left.

Once the repository is created on GitHub, follow these steps on your
local computer:

1. `mkdir merge-test`
2. `cd merge-test`
3. `touch merge.py`
4. `git init`
5. `git add .`
6. `git commit -m "initial commit"`
7. `git remote add origin <the_url_to_your_repo>`
8. `git push -u origin main`
9. `code .`

**Engineers**

Once the git manager has added you as a collaborator, you will receive and email to
confirm you as a collaborator to the repo the git manager has created. Check your email
(it could take a few minutes to come through) and click the confirmation link. Or approve it via the notification recieved in github.

After Git manager has pushed their code:

1. `git clone <url>`
2. `cd merge-test`
3. `code .`

## Making Your First Contributions

**All Students**

- Check out a new feature branch with  ```git checkout -b somefeature``` (call it whatever you like) and edit the merge.py any way you like.

- Commit your changes and push them to the remote repo using this command
  `git push origin <branch name>`. 

- Open a pull request on Github to merge the
  changes from your feature branch into `main`.

- Each student should add a comment to the PR! It should be an inline comment
  asking a question about the code, a suggestion or just adding an observation!

- If there are no conflicts, merge your pull request and delete your feature
  branches!

- If there are merge conflicts resolve them through github. You will then need
  to `git pull` the latest changes, resolve any conflicts locally, then `commit`
  and push again.


