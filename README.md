# 🎓 Git-Terminal Course Registry

Welcome to the official Course Registry! This project is a living document of everyone who has mastered the Git terminal workflow. To graduate, you must manually register your "Tile" in the source code via a Pull Request.

## 🚀 How to Contribute

Follow these steps exactly as they appear to add your name to the wall.

### 1. Clone the Repository

Open your terminal and clone the project to your local machine:

```bash
git clone [YOUR-REPO-URL]
cd git-terminal-course-registry

```

### 2. Create a New Branch

Never work directly on the `main` branch. Create a unique branch for your entry:

```bash
git checkout -b registry/add-[your-username]

```

### 3. Add Your Information

1. Open `index.html` in your code editor.
2. Locate the section marked ``.
3. Copy an existing `<div class="registry-tile">...</div>` block.
4. Paste it below the others and update the following:
* **Name:** Change `@YourNameHere` to your GitHub handle.
* **Timestamp:** Update the date and time.
* **Comment:** Write a brief note about your experience.



### 4. Commit and Push

Save your file and run the following commands:

```bash
git add index.html
git commit -m "Registry: Added [Your Name]"
git push origin registry/add-[your-username]

```

### 5. Open a Pull Request

1. Go to the repository on GitHub.
2. You will see a "Compare & pull request" button. Click it.
3. Add a title like `Registry Entry: [Your Name]` and submit.

---

## 🛠 Project Rules

* **Don't overwrite others:** Ensure you are adding a *new* div, not deleting someone else's.
* **Format matters:** Keep the HTML structure intact so the styling doesn't break.
* **Merge Conflicts:** If someone else pushed a change while you were working, you may need to `git pull origin main` and resolve conflicts!

---
