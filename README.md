# PLPBasicGitAssignment

**These are the steps I follwed in creation of the text file.**

1. **Task 1: Repository Setup*
    1. Open your web browser, go to GitHub, and log in to your account.
        2. Create a New Repository:
        3. Click the "+" icon in the top right corner of the page and select "New repository".
        4. Name the repository "PLPBasicGitAssignment".
        5. Check the box to initialize the repository with a README file.
        6. Click "Create repository"

2. **Task 2*  : Open your file explorer and create a new folder named "PLPBasicGitAssignment". using the terminal

    *Git initialization:*  In the terminal or command prompt, run the following command
             (git init) This initializes an empty Git repository in the folder.
    
    *Connecting to GitHub:* in the terminal or command prompt, run the following command, replacing <repository-url> with the URL of your GitHub repository:  
    (git remote add origin https://github.com/georgeklaus/PLPBasicGitAssignment.git)

3. *Task 3* : Making changes
        Create hello.txt:
         Create a new text file named hello.txt and add the content "Hello, Git!"
        (echo "Hello, Git!" > hello.txt)

   *Committing Changes:*
     Stage the Changes:
       In the terminal or command prompt, run: (git add hello.txt)
    
    *Commit the Changes:* (git commit -m "Add hello.txt with a greeting")

4. *Task 4: Pushing to GitHub* 
    Run the following command to push your committed changes to the GitHub repository:
        (git push -u origin main)

5. *Task 5: Verification* 
     Open your web browser and go to your GitHub repository.
Verify that the hello.txt file and its commit message "Add hello.txt with a greeting" are present.








   
