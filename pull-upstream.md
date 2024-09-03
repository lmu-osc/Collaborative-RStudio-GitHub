# Pull upstream repository into your fork

***

To integrate all the contributions made to the original repository into your local repository, you may think that you could first integrate the changes from the original repository into your fork (your GitHub version) and then pull your fork (to update your local copy), but this is not possible. You will need to shortcircuit this by pulling the original repository into your local repository directly (and then push the local new changes to your remote version on GitHub). This means that this operation needs to happen locally, in RStudio. Because you will not be pulling from your fork (your remote GitHub) but from the original repository, and that this isn't a daily operation, you do not have a shortcut for this in RStudio. This operation needs to be instructed in the command line, in the Terminal tab of RStudio.

1. **RStudio**: go to the Terminal tab of Rstudio 

2. **Terminal**: first make sure you are on the branch you wish to receive the modifications (today we didn't create branches other than the default one called 'main') by typing:  
   ```
   git checkout main
   ```

3. **Terminal**: type the command to pull the original repository and branch you wish to obtain locally which has the format: `git pull git@github.com:ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git` where you would replace original owner and repository to the appropriate names. Here: 
   ```
   `git pull git@github.com:lmu-osc/Collaborative-RStudio-GitHub.git`
   ```

    ![](./assets/command-line.png)

4. **RStudio**: check in the Files tab that the new contributions appeared.

5. **RStudio**: push those local changes to your GitHub repository (you can do this from the command line by typing `git push`)

    ![](./assets/final-push.png)


You are done!

***

