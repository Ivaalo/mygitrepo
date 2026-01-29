# Learning Git

I'm following a tutorial
So, if I get this:

- Going to a folder, then create a git repo
```bash
cd myfolder
git init
```

- Get the status/branch
```bash
git status
```

- Select the branch you want to work in
```bash
git branch -M branchName #main/master for the root one;
```

- Modify your files, add it to the queue, then create a safe file (commit)
```bash
git add MYFILE
git commit -m "My modification"
```

- Authentificate on GitHub, then add your online repo
```bash
gh auth login
# follow the steps
git remote add origin link_to_the_repo
```

- Then push to the online repo
```bash
gh push -u origin main
```

- Create a branch
```bash
git checkout -b myNewBranch
```

- List all branches
```bash
git branch -a
```

.gitignore contains the files it ignores, like passwords
After that, you can add all files with :
```bash
git add .
```