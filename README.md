# Git-Taskk

## 1. What is the difference between Git and GitHub?

- **Git** is a Distributed version control system. It helps you track code changes on your computer  
- **GitHub** is the platform. It lets you store that code online, share it, and collaborate with others.

## 2. Explain the difference between `git pull` and `git fetch`?
- **git fetch** gets the latest changes from the remote repo — but keeps them in the background.
- **git pull** does the same, but also updates your code with those changes right away.

## 3. What is the purpose of `.gitignore` file?
- The **gitignore** file tells Git to ignore certain files or folders — like temporary files, secrets, or stuff you don’t want to upload.

## 4. Describe the steps to contribute to an open-source project on GitHub?

1. **Fork** the project (make your own copy).
2. **Clone** it to your computer:
   ```bash
   git clone https://github.com/your-username/project-name.git
   ```
3. Create a new branch to work on:
   ```bash
   git checkout -b my-feature
   ```
4. Make your changes, then commit them:
   ```bash
   git add .
   git commit -m "Add: my feature or fix"
   ```
5. Push your branch to your GitHub fork:
   ```bash
   git push origin my-feature
   ```
6. Open a **Pull Request** on the original repository.



  
