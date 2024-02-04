# Week2-Task
To establish a GitHub repository for publishing a file:

1. Create a New Repository:
2. Initialize this repository with a README.

3. Clone the Repository:
   - On the repository page, click on the "Code" button.
   - Copy the URL.
CODE:
   bash
   git clone <repository_url>
   
   Replace <repository_url> with the copied URL.

4. Navigate to the Local Repository:
   CODE:
   bash
   cd <repository_directory>

   Replace <repository_directory> with the name of local repository.

5. Put File in the Local Repository:
   Move or copy the file you want to publish into the local repository.

6. Add, Commit, and Push Changes:
   CODE:
   bash
   git add .
   git commit -m "Initial commit: Add file for publication."
   git push origin main
   

   Replace "main" with the name of your default branch if it's different.


