# Push-directories-into-github
This give you the steps to push the directories from your terminal into your github
# How to Push Directories to GitHub

Follow these steps to push your directory to GitHub:

1. **Navigate to the directory**  
   ```sh
   cd /path/to/your/project
2. **Initialize Git**
   ```sh
   git init

3. **Add Remote Repository**
   ```sh
   git remote add origin <link_of_repo>

4. **Add Files to Staging Area**
   ```sh
   git add .
  

5. **Commit the Changes**
   ```sh
   git commit -m "<your-comment>"

6. **Push to GitHub**
   ```sh
   git push https://<your-username>:<your-token>@github.com/<your-username>/<repo-name>.git

