# 📘 GitHub Quick-Start Guide for IT Assistants

Welcome! This guide is designed for IT assistants and beginners who have never used GitHub before. Come back to these chapters anytime you feel confused about what a term means or what button to click next.

---

## 📑 Table of Contents
1. [Chapter 1: The 6 Words You Need to Know](#chapter-1-the-6-words-you-need-to-know)
2. [Chapter 2: How Branches Work (Simply)](#chapter-2-how-branches-work-simply)
3. [Chapter 3: The 5-Step Daily Routine](#chapter-3-the-5-step-daily-routine)
4. [Chapter 4: Branch Naming & Best Habits](#chapter-4-branch-naming--best-habits)
5. [Chapter 5: "I'm Confused!" Quick Rescue FAQ](#chapter-5-im-confused-quick-rescue-faq)

---

## Chapter 1: The 6 Words You Need to Know

GitHub uses technical words for very simple everyday actions:

| GitHub Word | Simple Analogy | What It Actually Means |
| :--- | :--- | :--- |
| **1. Repository (Repo)** | 📁 A Project Folder | The main folder on GitHub that holds all files and history for one project. |
| **2. Main Branch (`main`)** | 🏆 The Official Master Copy | The live, trusted version of the project that everyone uses. |
| **3. Branch** | 📝 A Safe Photocopy / Save Slot | Your personal copy of the project where you can make edits without breaking `main`. |
| **4. Commit** | 💾 Clicking "Save" + a Note | Saving changes on your branch with a short summary of what you changed. |
| **5. Pull Request (PR)** | 👀 "Please Review My Draft" | Asking your team to check your branch before combining it into `main`. |
| **6. Merge** | 🚀 Publishing Your Changes | Combining your approved branch back into the official `main` branch. |

---

## Chapter 2: How Branches Work (Simply)

> ⚠️ **The Golden Rule of GitHub:**  
> Never edit files directly inside `main`. Always create your own branch first!

When you create a branch, GitHub makes a safe parallel copy for you:

```text
main (Official):     ───●──────────●────────────────────●─── (Updated & Safe!)
                         \                            /
your-branch (Draft):      └──● (Edit 1) ──● (Edit 2) ─┘
                          ↑                          ↑
                   1. Create Branch           4. Merge via PR
```

* **You cannot break the live project:** Anything you do on `your-branch` stays isolated until it is reviewed and merged.
* **Easy to undo:** If an experiment goes wrong, simply delete the branch and start fresh from `main`.

---

## Chapter 3: The 5-Step Daily Routine

Every time you need to add or edit something on GitHub, follow these **5 steps**:

### Step 1: Create Your Branch
* Go to the main repository page.
* Click the **branch dropdown** in the top-left corner (it usually says `main`).
* Type a short name for your task (e.g., `update-printer-guide`) and click **Create branch**.

### Step 2: Make Your Changes
* Open the file you want to edit and click the **Pencil icon (✏️ Edit this file)**, or click **Add file** to upload/create a new one.

### Step 3: Commit (Save) Your Changes
* Click the green **Commit changes...** button in the top-right corner.
* Write a clear 1-sentence note explaining what you did (e.g., *"Added new helpdesk phone number"*).
* Make sure it commits to your branch, then confirm.

### Step 4: Open a Pull Request (PR)
* Go back to the repository page and click the yellow banner button **"Compare & pull request"** (or go to the **Pull requests** tab → **New pull request**).
* Click **Create pull request**.

### Step 5: Merge & Delete Branch
* Once your changes look good (or a teammate approves them), click the green **Merge pull request** button → **Confirm merge**.
* Click **Delete branch** to clean up your temporary workspace. Your changes are now live in `main`!

---

## Chapter 4: Branch Naming & Best Habits

Use short, lowercase names with hyphens (`-`) describing the task:

* ✅ **Good:** `update-wifi-guide`, `fix-backup-script`, `add-new-hire-checklist`
* ❌ **Avoid:** `test1`, `my-branch`, `final-v2-new`

> 💡 **Pro Habit:** Keep **one task per branch**. Once that task is merged, delete the branch and create a brand-new branch next time!

---

## Chapter 5: "I'm Confused!" Quick Rescue FAQ

**Q: How do I know which branch I'm currently inside?**  
Look at the button in the top-left corner above the file list (next to the `🔀` icon). The name shown there is your active branch.

**Q: I committed my changes, why aren't they showing up on `main`?**  
Because they are safely stored inside your branch! Complete **Step 4 (Pull Request)** and **Step 5 (Merge)** to bring them into `main`.

**Q: I made a mistake on my branch. Did I break the official project?**  
No! `main` is completely safe. Go to [Your Branches](https://github.com/NASCH01/Test1/branches/yours), click the trash can icon (`🗑️`) next to your branch to delete it, and create a fresh one.

**Q: Should I delete my branch after merging?**  
Yes! Once merged, your work is permanently saved in `main`. Deleting the branch just removes the temporary draft copy.
