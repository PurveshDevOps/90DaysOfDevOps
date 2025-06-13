![git_basics_task_1_result_3](https://github.com/user-attachments/assets/0b827c60-e6be-4716-812c-7bc261222c61)
![git_basics_task_1_result](https://github.com/user-attachments/assets/8c85d143-6309-4fce-8b7f-84a0c8432ad3)
![git_basics_task_1](https://github.com/user-attachments/assets/9e3f5928-a7ac-4492-8320-c13766b821fa)
![git_basic_task_1_result_2](https://github.com/user-attachments/assets/f3738e3f-df39-4e7b-90b2-026ba02fbfbd)

🚀 **Step-by-Step Solution**  

1️⃣ Fork the Repository**  
🔹 Go to the original repository on GitHub (e.g., `github.com/original/repo`).  
🔹 Click the **Fork** button (top-right).  
✅ Now, you have a copy under your GitHub account: `github.com/your-username/repo`.  

2️⃣ Clone Your Fork Locally**  
🔹 Copy your fork’s URL:  
   - Click **Code** (green button) → **HTTPS** → Copy the URL (`https://github.com/your-username/repo.git`).  
🔹 Run in **terminal**:  
   ```bash
   git clone https://github.com/your-username/repo.git
   cd repo
   ```  
✅ Your repo is now on your machine!  


3️⃣ Create a Feature Branch**  
🔹 Make a new branch for your changes:  
   ```bash
   git checkout -b feature-branch
   ```  
🔹 Add a new file or modify existing ones:  
   ```bash
   echo "New Feature" >> feature.txt
   ```  

4️⃣ Commit Your Changes**  
🔹 Stage and save your work:  
   ```bash
   git add .
   git commit -m "Added a new feature"
   ```  
📝 **Pro Tip**: Use a clear commit message!  

5️⃣ Push to GitHub**  
🔹 Upload your branch to your fork:  
   ```bash
   git push origin feature-branch
   ```  
🌐 **Output**: A new branch appears in your GitHub fork.  

6️⃣ Open a Pull Request (PR)**  
🔹 Go to your fork on GitHub.  
🔹 Click **Pull Requests** → **New Pull Request**.  
🔹 Select:  
   - **Base repo**: `original/repo` (main branch).  
   - **Head repo**: `your-username/repo` (`feature-branch`).  
🔹 Add a title/description, then click **Create PR**.  

7️⃣ Review & Merge**  
👀 Request a review from collaborators.  
🔄 Once approved, click **Merge Pull Request**!  
🎉 **Congrats!** Your changes are now in the main project.  

