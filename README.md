Git Command Summary:
───────────────────────────────────────────────────

1. VERSION CHECK
   git --version         → Check installed Git version

2. CONFIGURATION
   git config --global   → Set your name/email for commits
   git config --list     → View all Git configurations

3. REPOSITORY SETUP
   mkdir GitDemo         → Create project folder
   cd GitDemo            → Enter the folder
   git init              → Initialize new Git repo

4. FILE OPERATIONS
   echo > welcome.txt    → Create file with content
   ls                    → List files
   cat welcome.txt       → Show file content

5. VERSION CONTROL
   git status            → Check untracked/staged files
   git add welcome.txt   → Stage file for commit
   git commit            → Open editor to write commit message

6. REMOTE OPERATIONS
   git remote add origin → Link to GitHub repository
   git push -u origin    → Push to remote (failed - repo missing)
   git branch            → Show current branch (master)

   
───────────────────────────────────────────────────
