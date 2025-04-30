 
# ✅ Day 1 – Git Setup and Repo Clone

This lab covers setting up Git on Windows, configuring your identity, and cloning your personal GitHub repository using the command line.

---

## 💻 Terminal Commands Used

```bash
# Step 1 – Navigate to the Documents folder
cd %USERPROFILE%\Documents

# Step 2 – Clone the repository from GitHub
git clone https://github.com/jonmcgurgan/JonathanM-CyberPortfolio.git

# Step 3 – Change into the repo directory
cd JonathanM-CyberPortfolio

# Step 4 – Create a file to confirm setup is complete
echo Day1_Setup_Complete.md > Day1_Setup_Complete.md

# Step 5 – Stage the new file for commit
git add .

# Step 6 – Commit the staged file with a clear message
git commit -m "Day 1 setup complete"

# Step 7 – Push the changes to the main branch on GitHub
git push origin main
```

---

## 🧠 What I Learned

- **Command Line Navigation**: Used `cd` to change directories and understood the importance of correct paths.
- **Git Basics**:
  - `git clone` to download a repo.
  - `git add .` to stage changes.
  - `git commit -m` to snapshot work.
  - `git push` to send it to GitHub.
- **Troubleshooting**: Fixed an identity error using:
  ```bash
  git config --global user.name "Jonathan McGurgan"
  git config --global user.email "jonmcgurgan@gmail.com"
  ```
- **Authentication**: Signed into GitHub using the Git Credential Manager popup.

---

## 🔧 Next Steps

- Ensure every future lab is saved in a **clearly named subfolder** (e.g., `Git-Basics`, `Network-Scanning`, `Password-Cracking`).
- Continue writing reflections like this to demonstrate learning and build a reference you can revisit anytime.

