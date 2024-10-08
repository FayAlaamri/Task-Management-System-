# Simple Task Management System Using Git
1. git init
Used: When I first started the project.
Explanation: I initialized a new Git repository in the project directory using git init. This created the .git folder, allowing Git to start tracking changes to the project files.

2. git status
Used: Throughout the project, before staging or committing changes.
Explanation: I frequently used git status to check the state of my working directory. It helped me see which files were modified, added, or deleted, and whether any changes were staged for commit. This command was essential in keeping track of what was happening in the repository at any given time.

3. git add
Used: After making changes to the tasks.txt file and creating new files.
Explanation: I used git add to stage the changes I made to the project. This command prepared specific files, like tasks.txt and the README.md, to be included in the next commit. I often used git add . to stage all modified files at once.

4. git commit
Used: Every time I made significant changes to the project that I wanted to save.
Explanation: I committed my changes using git commit -m "commit message". Each commit represented a snapshot of the project at that point in time, with a message describing what changes were made, like "Add initial tasks" or "Update task descriptions."

5. git checkout -b
Used: When I needed to create separate branches to work on different features.
Explanation: I used git checkout -b <branch-name> to create and switch to new branches, like feature/add-tasks and feature/remove-tasks. This allowed me to work on new tasks or features without affecting the main master branch.

6. git merge
Used: When I finished working on a feature branch and wanted to integrate it into the main branch.
Explanation: After completing the work on the feature/add-tasks branch, I merged it into the master branch using git merge feature/add-tasks. This combined the changes from the feature branch into the main project. I also merged the feature/remove-tasks branch into master, resolving conflicts as necessary.

7. git rebase
Used: To integrate changes from one branch onto another while keeping a clean history.
Explanation: After making some updates on a branch called feature/update-tasks, I used git rebase master to rebase my changes onto the master branch. This allowed me to keep a linear commit history without unnecessary merge commits.

8. git revert
Used: When I needed to undo a mistake that was committed.
Explanation: I made an incorrect change to tasks.txt and committed it by mistake. I used git revert <commit-hash> to create a new commit that undid the incorrect change, without rewriting the project history.

9. git reset
Used: When I wanted to reset the project back to a specific previous commit.
Explanation: I understand the different uses of git reset, but in this instance, I opted for git revert because I had already committed the changes. Using git reset --hard <commit-hash> would have discarded all changes made after that commit, which wasn't suitable for my situation. Instead, I needed a way to undo the recent incorrect changes while preserving the commit history, so I chose to revert the last commit instead.
10. git log
Used: To view the history of commits in the project.
Explanation: I used git log to see a detailed history of all commits, including their messages, authors, and dates. This helped me track the progress of the project and see what changes had been made over time.

11. git log --oneline --graph
Used: To visualize the commit history in a compact and graphical format.
Explanation: I used git log --oneline --graph to get a concise view of the commit history, with each commit displayed on a single line. The --graph option showed a visual representation of branching and merging, which made it easy to see how branches were connected.

12. git push
Used: To upload the changes from my local repository to the remote repository on GitHub.
Explanation: After committing my changes locally, I used git push origin master to push my changes to the master branch on GitHub, making them available in the remote repository for others (or myself) to access.

13. git remote add
Used: When I first set up my project to be tracked on GitHub.
Explanation: After creating a repository on GitHub, I linked it to my local project by using git remote add origin <https://github.com/FayAlaamri/Task-Management-System-.git>. This allowed me to push changes to the remote repository and pull updates from it later on.

These commands were essential in managing the project, tracking changes, resolving conflicts, and collaborating with GitHub. Each one served a specific purpose, from initializing the repository to visualizing the project history.