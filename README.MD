# How to Use Git, Webstorm, and GitHub
1. In order to use GitHub we will first need to create
a GitHub account and download Webstorm and Git to be 
able to connect with GitHub.
   2. You create a GitHub account at https://github.com/join
   3. To Download and Install the latest Git navigate to https://git-scm.com/downloads
   4. To Download and Install Webstorm navigate to https://www.jetbrains.com/webstorm/


2. Once installed, you want to open Webstorm 

3. Navigate to settings by pressing Ctrl+Alt+S

4. On the left side of the screen you will see a panel. Click Version Control > GIT 
 
5. Change the Path to Git executable to C:\Program Files\Git\bin\git.exe. By clicking on the folder icon next to Test

6. Click Test to make sure that Webstorm is connected to Git.

7. If Git is installed correctly, you should get the message “Git Executed Successfully.”
   
8. Click OK to exit 

9. Click “Create New Project” on the Webstorm main page.
   
10. Rename “untitled” with the name you want

   For example,
    ``` C:\IS117Download\Webstorm\untitled``` becomes ```C:\IS117Download\Webstorm\IS117DemoS20 ```

11. Click ‘Create’
    
12. Once your screen change create a new file by navigating to File > New > HTML File
    
13. Name the file: index

14. You should see the index.html file starting with “<!DOCTYPE html>”
    
15. Make some changes after the <body>

    For example, add: ```<p> My first paragraph </p>```


16. Navigate to the top menu bar and click on VCS > Create Git Repository
    
17. You will have a "Select Directory where the new Git repository will be created" screen. Make sure the path is same as your project filename (match #10)
    
18. Click OK

19. Commit the changes to GIT: VCS>Git > Commit File  
    
20. Click on the checkbox next to index.html since this is the file that needs to be committed
    
21. Add a commit comment in “Commit Message”. This commit message is so you explain what you did in a few words. 

22. Click commit. 

    i. If this is the first commit ever, you will have a dialog box open. Set the Git username and email. Your username can be your name, and for the email use the email you used to create your GitHub account.

    ii. Click Set and Commit


23. You will now add the project to GITHUB. Navigate to  VCS > Import into Version Control > Share Project on Github. Your repository name is the name you replaced with “untitled” (What you renamed in #10). The “Share by” should be your Github link.
    (ie. https://github.com/jvf7)

24. Click Share. If all goes well you will receive a message “Successfully shared project on GitHub.”
    
25. Go to your GitHub account and you should see your file on the Internet
    
26. Now add a new file to the GitHub repository by navigating to Create>new File
    
27. Name it README.MD
    
28. Add some text below the tab ```<>Edit new file``` and commit.
    
29. Go back to Webstorm and make a change to your body by adding a new line to the index.html file.

30. Commit to Git: VCS >Git >Commit. Add the Commit comment and click Commit
    
31. You will be presented to push the commit change to Github: VCS > Git > Push
    
32. You will be presented with Push rejected because the system knows there is a file on GitHub named README.MD
    
33. Click on Merge. This will synchronize your GitHub account and your local machine 

34. You should now see the README.MD file under your project folder that contains the index.html file
    
35. To see the second line you added that was committed go back to your browser that has you signed into your GitHub account
    
36. You should see your new line on GitHub in your index.html file
    
37. Congratulations!!! You now know how to create files on Webstorm and GitHub.



