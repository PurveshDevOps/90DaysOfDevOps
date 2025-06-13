![git_stashing_code](https://github.com/user-attachments/assets/cf59e4bf-8788-4998-af1d-b552238350d9)

💡 What is "Stash" in Git?

Imagine you're working on a document, but halfway through, you suddenly need to switch and work on something else. You’re not ready to save your changes permanently yet, but you don’t want to lose them either.

In Git, **"stashing"** is like putting your current work into a **temporary drawer**. You’re not throwing it away, and you’re not saving it to the final version. You're just **keeping it safe to finish later**.

🗂️ Here's how it works:

* You **stash** your changes: This means you put them away temporarily.
* You switch to something else (maybe fix something urgent).
* When you're ready, you **"pop" the stash**: This means you take your work back out of the drawer and continue where you left off.

 🎯 Why use Git Stash?

Because sometimes:

* You’re in the middle of something...
* But you need to pause and do something else urgently...
* And you don’t want to lose your current work or save it permanently yet.

Git Stash is like a **"pause and save for later"** button.


📌 **When to Use Git Stash**

Use `git stash` when:

* You're in the **middle of some work**, but need to **pause and switch to something else**.
* You’re **not ready to save/commit** your changes, but don’t want to lose them.
* You want to **quickly clean your working directory** to check out another branch or pull new updates.

🔄 **Git Stash Pop vs. Git Stash Apply**

| Command           | What it does                                                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| `git stash apply` | 📥 Applies the stashed changes to your current work, **but keeps the stash** (you can reuse it).                                |
| `git stash pop`   | 📤 Applies the stashed changes **and deletes them** from the stash (like taking them out of the box and throwing the box away). |

✅ Quick Summary:

* Use `apply` if you might want to **reuse or keep** the stash.
* Use `pop` if you’re **done with the stash** and don’t need it anymore.

