
[git-cheat-sheet.pdf](https://github.com/user-attachments/files/18080197/git-cheat-sheet.pdf)

![image](https://github.com/user-attachments/assets/46e13908-921f-430e-98ee-95c1a4d95d4f)

![image](https://github.com/user-attachments/assets/7a3f77d4-3baa-48c7-aae0-8eb93607f9e4)

![image](https://github.com/user-attachments/assets/613abd31-2155-449f-9542-97d15cc462ad)


Create repositories
A new repository can either be created locally, or an existing repository can be cloned. When a repository was initialized locally, you have to push it to GitHub afterwards.

$ git init

The git init command turns an existing directory into a new Git repository inside the folder you are running this command. After using the git init command, link the local repository to an empty GitHub repository using the following command:

$ git remote add origin [url]

Specifies the remote repository for your local repository. The url points to a repository on GitHub.

$ git clone [url]

Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits

The .gitignore file
Sometimes it may be a good idea to exclude files from being tracked with Git. This is typically done in a special file named .gitignore. You can find helpful templates for .gitignore files at github.com/github/gitignore.

Glossary
git: an open source, distributed version-control system
GitHub: a platform for hosting and collaborating on Git repositories
commit: a Git object, a snapshot of your entire repository compressed into a SHA
branch: a lightweight movable pointer to a commit
clone: a local version of a repository, including all commits and branches
remote: a common repository on GitHub that all team members use to exchange their changes
fork: a copy of a repository on GitHub owned by a different user
pull request: a place to compare and discuss the differences introduced on a branch with reviews, comments, integrated tests, and more
HEAD: representing your current working directory, the HEAD pointer can be moved to different branches, tags, or commits when using git switch
