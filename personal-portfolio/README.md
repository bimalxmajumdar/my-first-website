# Git Push Instructions

1. Initialize Git repository (if not already done):
```bash
git init
```

2. Add all files to staging:
```bash
git add .
```

3. Commit your changes:
```bash
git commit -m "Initial commit"
```

4. Add remote repository (only first time):
```bash
git remote add origin https://github.com/yourusername/your-repo-name.git
```

5. Push to GitHub:
```bash
git push -u origin main
```

Note: 
- If you're using 'master' branch instead of 'main', replace 'main' with 'master'
- Make sure you have created the repository on GitHub first
- Ensure you're logged in to GitHub in Git Bash (`git config --global user.name "Your Name"` and `git config --global user.email "your@email.com"`)
