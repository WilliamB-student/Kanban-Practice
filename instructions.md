# Instructions: Kanban Fundamentals with GitHub

Follow the steps below to complete the **Kanban Fundamentals** assignment.  
Screenshots and your reflection will be submitted in Canvas.

---

## 1. Make a new GitHub Repository
1. In **GitHub Desktop**, select **File → New Repository**.  
2. Name the repository "Kanban Practice".  
3. Add all of the zip file contents to this new repository's folder.  
4. In GitHub Desktop, commit the files (e.g., "Add starter files") and click **Publish repository**.  

---

## 2. Create Issues (on GitHub.com)
Some tasks live outside Desktop, so you’ll create Issues in the browser.  

1. Go to your repository on **GitHub.com**.  
2. Open the **Issues** tab.  
3. Create at least **5 Issues**.  
   - Each Issue should represent a distinct task (see [`sample-issues.md`](sample-issues.md) for examples).  
   - One of them must be titled **Add my name and date to intro.txt**. You will close it with a commit in Step 3.  
4. Note that Issue's number (e.g., `#3`).  

---

## 3. Link a Commit to an Issue (in GitHub Desktop)
This is a critical step: learn how to connect your code changes to an Issue.  

1. **Edit a File Locally**

   * Open `intro.txt` in your repo folder using a text editor (e.g., VS Code, Notepad++, or TextEdit).
   * Replace `[STUDENT NAME]` with your name, and add today’s date on the next line.
   * Save the file.

2. **Commit in GitHub Desktop**

   * Open GitHub Desktop.
   * You should see your file changes listed.
   * In the **Summary** box, type a commit message that references the Issue number from Step 2:

     ```
     Added my name and date to intro.txt (Fixes #3)
     ```
     Replace `#3` with your actual Issue number.
   * Click **Commit to main**.
   * Click **Push origin** to sync changes back to GitHub.

3. **Check the Issue on GitHub**

   * Go back to the Issue on GitHub.com.
   * Scroll to the bottom. You’ll see your commit message linked there.
   * Because you used **Fixes #3** and the commit is on the main branch, the Issue **closes automatically**.
   * If you want to just reference an Issue without closing it, use:

     ```
     Updated intro.txt (Refs #3)
     ```

### ✅ What You’ve Learned

* `Fixes #<issue number>` links a commit to an Issue **and closes it automatically**.
* `Refs #<issue number>` links a commit to an Issue **without closing it**.
* This creates **traceability**: anyone can see *what code changes resolved which task*.

---

## 4. Create a Kanban Board (GitHub Projects)
1. In your repo on GitHub.com, click the **Projects** tab.  
2. Click **New project**.  
3. Under "Start from scratch," choose **Board**.  
4. Name it: **Kanban Fundamentals – [Your Last Name]**, then click **Create project**.  
5. Make sure the board has three columns: **Todo**, **In Progress**, and **Done**. The Board layout usually starts with these; add any that are missing.  

---

## 5. Add Issues to Your Board
1. At the bottom of the **Todo** column, click **+ Add item**.  
2. Type `#`, pick your repository, and select an Issue. Repeat until all of your Issues are on the board.  
3. Open Issues go in **Todo**. The Issue you closed in Step 3 can go in **Done**.  

---

## 6. Organize & Assign
1. Add **labels** to at least 3 Issues (e.g., Documentation, Enhancement, Bug).  
2. Assign yourself as the responsible person on at least 2 Issues.  
3. Add at least one **due date**. The Board layout has no due date field, so create one first:  
   - Switch your project to **Table** view.  
   - Click the **+** at the right end of the column headers and choose **New field**.  
   - Name it "Due date," pick **Date**, and click **Save**.  
   - Set a date on at least one Issue, then switch back to **Board** view.  

---

## 7. Move Issues Through the Workflow
- Drag at least **2 Issues** to **In Progress**.  
- Have at least **1 Issue** in **Done**.  

---

## 8. Make a Final Local Commit
Before finishing:  
1. Open `README.md` on your computer.  
2. Add one line at the bottom:  
   ```
   Completed Kanban Fundamentals – [Your Name]
   ```  
3. Commit this change in **GitHub Desktop**.  
4. Push your commit to GitHub.  
5. Optionally, link this commit to another Issue (e.g., *“Add completion note to README.md”* → `Closes #5`).  

---

## 9. Submit Your Work
1. Take **screenshots** of your Project board showing Issues in all three columns (*Todo*, *In Progress*, *Done*).  
2. Write a **short reflection (3–5 sentences)** that addresses:  
   - How does Kanban help visualize and manage analytics work?  
   - What benefits do you see from linking Issues to commits in GitHub Desktop?  
   - How might Kanban help you (or your team) avoid bottlenecks and stay organized in a real analytics project?  
3. Submit your screenshots and reflection in Canvas as one Word document or PDF.  

---

## ✅ Checklist Before Submitting
- [ ] Created and published the "Kanban Practice" repo in GitHub Desktop.  
- [ ] Created at least 5 Issues on GitHub.  
- [ ] Edited `intro.txt` locally and closed its Issue with a linked commit.  
- [ ] Created a Project board with Todo, In Progress, and Done columns.  
- [ ] Added your Issues to the Project board.  
- [ ] Added labels, assignees, and at least one due date.  
- [ ] Moved Issues across *Todo*, *In Progress*, *Done*.  
- [ ] Made a final commit to `README.md` in GitHub Desktop.  
- [ ] Captured board screenshots and wrote the reflection.  

---

## 📖 Helpful Resources
- [Quickstart for Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects)  
- [About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)  
- [Using issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues)  
- [Tracking your work with issues (overview)](https://docs.github.com/en/issues/tracking-your-work-with-issues)  

---
