# GitHub Team Collaboration Guide

### Step 1: Fork the Repository (Team Leader)
The team leader forks the repository to create a copy for collaboration.

### Step 2: Clone the Repository (Team Leader)
```bash
git clone [repo clone link]
cd repo-name
```

### Step 3: Set Up the Project
After cloning, ensure the project runs properly:
```bash
npm install  # Install dependencies
npm run dev  # Run the project locally
```
If the project runs successfully, proceed to the next step. Otherwise, consult the team leader.

### Step 4: Create a New Branch
Creating a new branch ensures that your changes are isolated from the main branch.
```bash
git checkout -b new-branch
# OR
git branch new-branch  # Create a new branch
git checkout new-branch  # Switch to the new branch
```

### Step 5: Make Changes and Push
After completing your task, add and commit your changes, then push them to your branch:
```bash
git add .
git commit -m "My first contribution added"
git push origin new-branch
```

### Step 6: Create a Pull Request
1. Go to your GitHub repository.
2. Navigate to the **Pull Requests** tab.
3. Create a new pull request for your branch.
4. Inform the team leader about the pull request.

#### Important Considerations:
- If this is your final commit for the current task, inform the team leader for review and merging.
- If further changes are needed, notify the team leader before merging. You can continue working on the same branch and push additional commits.

### Step 7: Await Approval
Once you reach this step, congratulations! 🎉 Wait for the team leader to review and merge your changes.

### Step 8: Sync Fork and Update for Further Contributions
If you want to contribute again:
```bash
git switch main
git pull origin main
```
Then, create another new branch and follow **Steps 4–7**.

### Step 9: Delete a Branch (If Needed)
#### Delete a Local Branch:
```bash
git branch -d branch-name  # If merged
git branch -D branch-name  # Force delete if not merged
```
#### Delete a Remote Branch:
```bash
git push origin --delete branch-name
```

### Step 10: Delete a Repository (If Needed)
1. Go to your GitHub repository settings.
2. Scroll down to the **Danger Zone** section.
3. Click **Delete this repository**.
4. Confirm by typing the repository name and clicking the delete button.

#### Note:
- If you need to modify previously accepted work, follow **Steps 4–6** again.
- **Do not push changes directly to the main branch.**

---
**Thank you for contributing!** 🚀 Your efforts are greatly appreciated. Feel free to collaborate and improve this project!

