# git-and-Github-using ![image](https://github.com/user-attachments/assets/ff1c56d2-8d56-4b93-9b3f-100a7fe90ff1)

How to add a new project into Github using VSCode
# Navigate to your project directory
```
cd /path/to/your/project
```

# Initialize a new Git repository
```
git init
git add .
# Commit with a descriptive message
git commit -m "Initial commit: Describe your project or changes"
```
# Or, if you want to add specific files
```
git add filename1 filename2
```
# Go to GitHub and create a new repository
# Copy the repository URL (use HTTPS or SSH)

# Add the remote repository
```
git remote add origin https://github.com/yourusername/your-repo-name.git
```

# For the first push to main branch
```
git push -u origin main
```
# For subsequent pushes
```
git push
```

Additional Tips:

Create a .gitignore file to exclude unnecessary files:
```
# Create .gitignore in project root
touch .gitignore

# Example contents to ignore
node_modules/
.env
*.log
```

Common Troubleshooting:

If you're using the default branch name master instead of main:
```
git push -u origin master
```


![image](https://github.com/user-attachments/assets/d4d2ff95-a8ef-445d-9b91-1296100ece09)

![image](https://github.com/user-attachments/assets/b2f170e0-b9eb-4bab-a854-f3e81a4fb924)

![image](https://github.com/user-attachments/assets/32f04262-dffa-490a-9e99-b73064ead4e8)

![image](https://github.com/user-attachments/assets/a93c6f1b-2dbe-441e-8c49-4004c8b06a68)

