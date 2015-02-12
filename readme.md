**Author:** *Harmony Betancourt*
**Class:** *DWP*
# Portfolio Deployment Plan #
Thank you for taking interest in my portfolio. To make changes, please follow my deployment plan below.
---
## Deployment Plan

1. Forking Git 
2. Create Local Clone
3. Sync Git
4. Making Changes
5. Check For Conflicts
6. Committing and Pushing
7. Saving Changes


---
## 1.  Forking Git ##
Using the github account at https://github.com/hb08/dwp.git
  1.  Click Fork in the top right-hand corner
  
## 2.  Creating Local Clone ##
After acquiring Git, copying the fork url, and navigating to your home directory for the files,
  1.  Type **git clone** *fork url* and *Enter*

## 3. Sync Git   ##
After copying url to clone of repository, and navigating into the fork cloned in step 2
  1.  Type **git remote -v** to view configured remote repositories 
  2.  Type **git remote add upstream** *fork url*  and *Enter*
    - Type **Git remote -v** and *Enter* to verify upstream is there 
  3.  Type **git fetch upstream** and *Enter* to fetch and store commits.

## 4.  Making Changes ##
Changes must be made within a text editor of your choice, and saved within or using the file structure of the existing project.

## 5.  Check For Conflicts ##
  1. Type **git checkout master** and *Enter* 
  2. Type **git pull** *fork link* **master** and *Enter*
    - Resolve any conflicts, commit and pull again
  3. Type **git merge upstream/master
    - Resolve any conflicts
  
## 6. Committing and Pulling ##
  1.  Type **git add -A** and *Enter*
  2.  Type **git commit -am ' _Appropriate Comment_ '** and *Enter*
  3.  Type **git pull origin master** and *Enter*
  		
## 7.  Saving Changes ##
  1. Type **git push origin** *fork name ex. master* and *Enter*

## 8.  Initiate Pull Request
  1.  Access branch on Github site
  2.  Click the "Compare and Review" button (Green button)
  3.  Once all changes have been reviewed, click the "Create Pull Request" button
  4.  Enter necessary information and click "Create Pull Request" button
  
 

