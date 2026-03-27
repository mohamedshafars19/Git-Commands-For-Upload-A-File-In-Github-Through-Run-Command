# Git-Commands-For-Upload-A-File-In-Github-Through-Run-Command

Git Commands (General Syntax)
# Go to your project folder
  cd "your-project-path"

# Initialize git
  git init

# Add all files
  git add .

# Commit files
  git commit -m "your commit message"

# Connect to GitHub repo
  git remote add origin https://github.com/username/repository-name.git

# Set main branch
  git branch -M main

# Push to GitHub
  git push -u origin main
  
⚠️ If Error Occurs
  git pull origin main --rebase
  git push origin main
  
🔁 For Future Updates
  git add .
  git commit -m "update message"
  git push
