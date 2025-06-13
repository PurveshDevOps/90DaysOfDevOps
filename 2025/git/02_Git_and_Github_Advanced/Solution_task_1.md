![git_advance_task_1_code](https://github.com/user-attachments/assets/a2235197-9569-4e9d-a9dc-4d330ca18a2f)
![git_advance_task_1](https://github.com/user-attachments/assets/88699eee-2c97-4c12-af6b-68c3863727ab)
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
