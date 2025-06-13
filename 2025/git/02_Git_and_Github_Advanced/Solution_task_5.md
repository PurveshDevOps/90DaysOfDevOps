![git_reset_soft](https://github.com/user-attachments/assets/23deffdd-0514-428a-b6a6-9c070d66effa)
![git_reset_mixed](https://github.com/user-attachments/assets/6d377bbe-8d1c-4d36-a79c-7f2bdd35c0f2)
![git_reset_hard](https://github.com/user-attachments/assets/2fd3e784-1a23-4fbc-a9fb-7c611610a2cc)
![git_rebase_code](https://github.com/user-attachments/assets/06ae1d93-56ef-4e58-93fb-cae84806bb7d)
### 🔄 What is **Git Rebase**?

**Git Rebase** takes:

* 🟢 Your work (commits from your branch)
* 🔵 The main work (commits from the main branch like `master` or `main`)

…and **re-arranges them into one neat, straight line** – as if **you wrote everything one after the other**.

🧱 It makes the project history **clean, simple, and easy to read** — like lining up bricks in one straight row.


🔁 Example (Fresher-friendly):

You have a `feature` branch and the main branch (`master`):

1. Your teammate added updates to `master` 🔵
2. You were working on your feature 🟢
3. To combine your work cleanly, you **rebase** — now your updates come **after** the master branch updates 📏


🤝 **Merge vs. Rebase**

| 🧩 Feature       | 🔀 Merge                                       | 🔄 Rebase                                  |
| ---------------- | ---------------------------------------------- | ------------------------------------------ |
| 🌳 History       | Keeps all history + creates a **merge commit** | Rewrites history into a **linear flow**    |
| 🧾 Extra Commits | Adds an extra “merge” commit                   | No extra merge commit                      |
| 🧼 Clean History | May look messy with many branches              | Cleaner, simpler history                   |
| 🛠️ Use When     | Team collaboration or preserving history       | Keeping personal branch clean before merge |


🧠 Best Practices for Rebasing

✅ **Use rebase for your own local branches** (before pushing):

* Keeps your branch clean and organized
* Makes your commits easier to review

🚫 **Don’t rebase shared/public branches**:

* Rewriting history that others are using can cause big confusion! 😵

