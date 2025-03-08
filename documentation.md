# TASK ONE
## Steps Followed
### 1. Repository Setup
- Created a new repository on GitHub: Nexascale-Collaboration
### 2. Clone Repository Locally
    git clone https://github.com/Better-Great/Nexascale-Collaboration.git
    cd Nexascale-Collaboration
### 3. Create a New Branch
    ```sh
    git checkout -b feature-update
    ```
### 4. Add and Commit Changes
- Created a README.md file and added a short introduction.
- Staged and committed the changes.
    ```sh
    git add README.md
    git commit -m "comments"
    ```
### 5. Push Branch to Remote Repository
    ```sh
    git push origin feature-update
    ```
### 6. Open a Pull Request (PR) on GitHub
- Navigated to the repository on GitHub.
- Opened a new pull request from feature-update to main.
- Reviewed the changes and submitted the PR.
### 7. Merge the Pull Request
- After reviewing, merged the PR into main.
### 8.  Pull Latest Changes Locally
    ```sh
    git checkout main
    git pull origin main
    ```


# TASK TWO
## Collaboration Task 
The collaboration task for **NexaScale**, completed by **Better-Great and Tosin**.  
The task demonstrates **Pair Programming**, where two developers work together to build a simple HTML and CSS webpage.  

## What is Pair Programming?
Pair Programming is a software development practice where two programmers collaborate at the same workstation.  
- One acts as the **Driver**, writing the code.  
- The other acts as the **Navigator**, reviewing and providing guidance.  

This method enhances **code quality, problem-solving, and knowledge sharing**.

---

## Steps We Took  

### **1. Repository Setup**
- One team member (**Owner**) created a new GitHub repository.
- The Owner invited the second team member as a collaborator.

### **2. Adding the Initial File**
- The Owner  which was **@mayasi** created an `index.html` file and pushed it to the `main` branch.

### **3. Collaborator's Contribution**
- The Collaborator cloned the repository:
  ```sh
  git clone git@github.com:mayasimi/nexushubcol.git
  cd nexushubcol
  ```
- Created a new branch named update-styles:
    ```sh 
    git checkout -b update-styles
    ```
- Added a styles.css file and modified index.html to include CSS.

### 4. Committing and Pushing Changes
- The Collaborator committed and pushed changes:
    ```sh
    git add .
    git commit -m "Added styles to index.html"
    git push origin update-styles
    ```
### 5. Creating a Pull Request (PR)
- The Collaborator opened a Pull Request on GitHub.
#### Pull Request Link
https://github.com/mayasimi/nexushubcol/pull/2

### 6. Review and Merge
- The Owner reviewed the PR and merged it into the main branch.
### 7. Pulling the Latest Changes
- Both members pulled the updated project
    ```sh
    git checkout main
    git pull origin main
    ```

