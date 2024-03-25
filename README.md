# Fork the repository on GitHub
# Clone the forked repository
git clone <your_fork_URL>
# Create a new branch
git checkout -b Griffins-coffee
# Make changes and commit
git add .
git commit -m "Griffins-coffee initial commit"
# Switch back to main branch
git checkout main
# Merge changes from feature branch
git merge Griffins-coffee
# Make conflicting changes
# Commit the changes
# Create a new branch to resolve conflicts
git checkout -b conflict-fix
# Resolve conflicts manually
# Add the resolved file
git add <filename>
# Commit the changes
git commit -m "Resolved conflict"
# Merge the conflict-fix branch back into main
git checkout main
git merge conflict-fix
