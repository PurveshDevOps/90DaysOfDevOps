![git_revert reset](https://github.com/user-attachments/assets/198ef293-3a28-47fd-a3fa-c8d3b48e9dcf)
![git_revert rebase_44](https://github.com/user-attachments/assets/98a42e99-2ec6-4836-a897-f3a327d6a453)
![git_revert rebase_3](https://github.com/user-attachments/assets/6228be93-2677-44b9-85a8-b3a5018ad8a4)
![git_revert rebase_2](https://github.com/user-attachments/assets/2effde76-9223-452e-9f3d-370b182c6d7b)
![git_reset_soft](https://github.com/user-attachments/assets/7b72a7b3-4efb-46e6-895c-e1f387b7564d)
![git_reset_mixed](https://github.com/user-attachments/assets/8aa1f7a8-9c49-4bfe-a63e-2b7a012bd55a)
![git_reset_hard](https://github.com/user-attachments/assets/2d551f90-a726-449a-b79f-2042054de102)
![git_rebase_code](https://github.com/user-attachments/assets/67d54a7a-01c1-405a-8f9a-4ef8ccba61c8)


🛠️ **Undoing Mistaken Commits in Git (Beginner-Friendly Guide)**

🧪 Step 1: Create and Commit by Mistake

```bash
echo "Wrong code" >> wrong.txt  # 📝 Create wrong.txt with wrong code
git add .                       # ➕ Stage the file
git commit -m "Committed by mistake"  # ❌ Commit made by accident
```

🔄 Ways to Undo the Mistaken Commit

1️⃣ **Soft Reset** – Keep changes **staged** (still ready to commit)

```bash
git reset --soft HEAD~1  # 🔙 Undo the commit, but keep changes staged ✅
```

🟢 Use this when: You want to **edit the last commit message** or fix something before recommitting.

2️⃣ **Mixed Reset** – Unstage changes, but **keep your code**

```bash
git reset --mixed HEAD~1  # 🧼 Unstage changes, but keep them in files 📝
```

🟢 Use this when: You want to **start staging again from scratch**.

3️⃣ **Hard Reset** – ⚠️ **Danger Zone!** All changes are removed

```bash
git reset --hard HEAD~1  # 💣 Deletes the commit and your code changes 🚫
```

🛑 Use this when: You want to **completely wipe out** the last commit and its changes. Be careful!

4️⃣ **Revert** – Safely undo a commit by making a new one

```bash
git revert HEAD  # 🩹 Creates a new commit that undoes the last one ✅
```

🟢 Use this when: You already **pushed the bad commit** to a shared repo and want to fix it safely.

📊 Difference Between `reset` and `revert`

| Command  | 🔁 What It Does                                      | ✅ Safe for Shared Repos?  |
| -------- | ---------------------------------------------------- | ------------------------- |
| `reset`  | **Moves** the commit pointer (can delete history)    | ❌ No (can mess up others) |
| `revert` | **Creates a new commit** that undoes previous commit | ✅ Yes                     |

📌 When to Use Each Method

* 🔧 **Soft Reset**: Fix or reword a recent commit 🛠️
* 📦 **Mixed Reset**: Start staging from scratch again 🎯
* 💣 **Hard Reset**: Remove all changes completely (only if local!) 🧹
* 🩹 **Revert**: Safely undo a commit already pushed to GitHub 🌍
