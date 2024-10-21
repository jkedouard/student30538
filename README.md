# PPHA 30538: Data and Programming in Python
## Fall 2024
## University of Chicago Harris School of Public Policy
## Peter Ganong and Maggie Shi

Welcome to the **new** student repository for PPHA 30538: Data and Programming in Python. 

# Repository Structure

Lectures are in both the `before_lecture` and `after_lecture` folders. `before_lecture` does not contain answers to in-class exercises, while `after_lecture` does. Within each folder ,each lecture will have its own folder with the following materials:
- **Quarto code**: `.qmd` files that are the source of the lecture slides.
- **Supporting materials**: Any images, data files, or external resources referenced in the slides.
- **Slides**: knitted PDF or HTML files that contain the slides used during the lecture.

Each problem set and mini-lesson will have their own folders within their respective folders. Kickoff slides (slides discussed before lecture starts) are all contained in `kickoff`.

---
# Accessing the Repository
## Step 1: Fork the Repository  
- Go to the [original repository](https://github.com/uchicago-harris-dap/student30538) on GitHub.  
- Click the **Fork** button in the upper-right corner of the repository page. This will create a personal copy of the repository in your GitHub account.

---

## Using GitHub Desktop

### Step 2: Clone Your Forked Repository  
1. Open **GitHub Desktop**.  
2. Click **File > Clone Repository**.  
3. Select the **"URL" tab** and paste in **https://github.com/uchicago-harris-dap/student30538**.
4. Choose a local directory where you want to clone the repository.  
5. Click **Clone**.

### Step 3: Sync Your Fork with the Original Repository  
1. Open the cloned repository in GitHub Desktop.  
2. Click **Repository > Repository Settings**.  
3. Under **Remotes**, click **Add Remote**.  
4. Set the name as `upstream` and paste the **https://github.com/uchicago-harris-dap/student30538** of the original repository:
   ```
   https://github.com/uchicago-harris-dap/student30538
   ```
5. Click **Save**.  
6. To fetch updates from the original repository, click **Fetch Origin** in the main GitHub Desktop window.  
7. When updates are available, click **Pull** to merge them into your local copy.

### Step 4: Push Changes to Your Fork  
1. After making changes, click **Commit to main** in GitHub Desktop.  
2. Add a commit message and click **Commit**.  
3. Click **Push Origin** to send the changes to your forked repository on GitHub.

---

## Using Command Line

### Step 2: Clone Your Forked Repository  
1. In your GitHub account, navigate to your **forked repository**.  
2. Click the green **Code** button and copy the **HTTPS URL**, **https://github.com/uchicago-harris-dap/student30538**.  
3. Open a terminal and run the following command:
   ```bash
   git clone **https://github.com/uchicago-harris-dap/student30538**
   ```

### Step 3: Set the Upstream Remote  
(Optional but recommended to keep your fork updated.)  
1. Navigate to the cloned repository in your terminal:
   ```bash
   cd student30538
   ```
2. Add the upstream remote:
   ```bash
   git remote add upstream https://github.com/uchicago-harris-dap/student30538
   ```
3. Confirm your remotes:
   ```bash
   git remote -v
   ```

### Step 4: Sync Your Fork with the Original Repository  
1. Fetch updates from the original repository:
   ```bash
   git fetch upstream
   ```
2. Merge the updates into your local branch:
   ```bash
   git merge upstream/main
   ```
   Replace `main` if the default branch has a different name (e.g., `master`).

### Step 5: Push Changes to Your Fork  
1. After making changes, stage and commit them:
   ```bash
   git add .
   git commit -m "Your commit message"
   ```
2. Push the changes to your fork:
   ```bash
   git push origin main
   ```

---


Feel free to reach out via EdDiscussion if you have any questions or run into any issues. Happy coding!
