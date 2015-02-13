**Author:** *Harmony Betancourt*
**Class:** *DWP*
# Portfolio Deployment Plan #
Thank you for taking interest in my portfolio. To make changes, please follow my deployment plan below.
---
## Deployment Plan
1. Making Changes
2. Check For Conflicts
3. Committing and Pushing
4. Merging and Testing
5. Test Server


---
## 1.  Making Changes ##
Changes must be made within a text editor of your choice, and saved within or using the file structure of the existing project.

## 2.  Check For Conflicts ##
  1.  Type **git checkout master** and *Enter* 
  2.  Type **git pull** *remote repo* **master** and *Enter*
      - Resolve any conflicts, commit and pull again
  
## 3. Committing and Pulling ##
  1.  Type **git add -A** and *Enter*
  2.  Type **git commit -am ' _Appropriate Comment_ '** and *Enter*
  3.  Type **git pull** *remote repo* **master** and *Enter*
  
## 4. Merging and Testing##
  1.  Type **git merge** *changeName*
      - Resolve any conflicts  
  2.  Type **git push** *fork name ex. master* and *Enter*	
  
## 5.  Test Server  ##
  1.  Notify team members of impending upload and testing
  2.  Type **git push** *staging server* **master**
  3.  Test again
  4.  Promote to Production
  5.  Test again
 
  
 
