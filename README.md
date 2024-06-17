# PLPBasicGitAssignment

**These are the steps I follwed in creation of the text file.**

1. **Task 1: Repository Setup*
    1. I opened my web browser (google chrome), to GitHub, and loged in to my account.
    2. Created a New Repository:
    3. Clicked the "+" icon in the top right corner of the page and selected "New repository".
    4. I nameed the repository "PLPBasicGitAssignment".
    5. I checked the box to initialize the repository with a README file.
    6. Finally clicked "Create repository" to create the repository

2. **Task 2*  : I opened my file explorer and created a new folder named "PLPBasicGitAssignment". using the terminal.

    *Git initialization:*  In the terminal, I run the following command
             (git init) This initialized an empty Git repository in the folder.
    
    *Connecting to GitHub:* in the terminal, I run the following command, replacing <repository-url> with the URL of my GitHub repository:  
    (git remote add origin https://github.com/georgeklaus/PLPBasicGitAssignment.git)

3. *Task 3* : Making changes
        Create hello.txt:
         I created a new text file named hello.txt and added the content "Hello, Git!"
        (echo "Hello, Git!" > hello.txt)

   *Committing Changes:*
     Stage the Changes:
       In the terminal, I run: (git add hello.txt)
    
    *Commit the Changes:* (git commit -m "Add hello.txt with a greeting")

4. *Task 4: Pushing to GitHub* 
    I run the following command to push my committed changes to the GitHub repository:
        (git push -u origin main)

5. *Task 5: Verification* 
    I opened my web browser and to my GitHub repository.
Then verified that the hello.txt file and its commit message "Add hello.txt with a greeting" are present. 


By following these steps and illustrations, I was able to successfully complete the project and had a functional Git repository both locally and on GitHub.