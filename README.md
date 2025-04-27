 📋 To-Do App - Git Branching Demonstration

# Overview

This project is a simple **To-Do List Application** designed to demonstrate practical use of **Git branching**.  
The goal was to showcase the creation, switching, and deletion of branches while maintaining a clean and organized workflow.

# Project Objective

- Implement basic Git operations in a real-world mini project.
- Understand how branches improve project structure and collaboration.
- Practice pushing local branches to a remote repository.



# Git Branching Operations Practiced

| Operation         | Purpose                                     | Example Command                           |
|-------------------|---------------------------------------------|-------------------------------------------|
| Create Branch     | Start a new feature or fix                  | 'git branch Branch1'                      |
| Switch Branch     | Move between features and tasks             | 'git switch Branch2'                      |
| Delete Branch     | Clean up finished or merged branches        | `git branch -d Branch3'                   |
| Push to Remote    | Share branch with team / backup remotely    | 'git push origin Branch1'                 |



# Current Branches on Remote

- 'main'
- 'Branch1'
- 'Branch2'
- 'Branch3'
- 'New-Branch'

✅ All branches were successfully pushed to GitHub for remote collaboration and visibility.

---

## How Git Branching Helped

- **Isolated Development**: Each branch handled a separate feature or fix without affecting others.
- **Clean Switchovers**: Easy to move between features without mixing code.
- **Safe Deletion**: Completed work was deleted after merging to keep the repo clean.
- **Remote Collaboration**: All branches visible on GitHub for traceability.

---

# Project Structure


/todo-app
 ├── index.html
 ├── style.css
 ├── app.js
 └── README.md


# Key Git Commands Used

bash
git branch <branch-name>             # Create a new branch
git switch <branch-name>              # Switch to an existing branch
git branch -d <branch-name>           # Delete a local branch
git branch -D <branch-name>           # Force delete a local branch
git push origin <branch-name>         # Push a branch to remote
git push origin --delete <branch-name> # Delete a branch remotely
git stash                             # Save temporary changes
git reflog                            # View and recover commit history




# Final Notes

This project highlights how even small-scale applications benefit immensely from using Git branching strategies.  
It reinforces industry best practices such as clean code management, isolated development, and safe feature integration.
