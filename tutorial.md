# **_Git and GitHub tutorial_**

## **I. Overview of Git and GitHub**
    
## **II. How to install Git and GitHub**
    Go to https://git-scm.com/downloads to install Git
    
   ![image](https://user-images.githubusercontent.com/73635652/101713001-54c58380-3ac9-11eb-9c17-fe094877a137.png)
   
    Log in your GitHub account by going to https://https://github.com/
   
   ![image](https://user-images.githubusercontent.com/73635652/101713472-4a57b980-3aca-11eb-8a4f-d457eb54b644.png)
    
## **III. Basic Git commands**   
### _1. Check git config_  
    git config -l (list everything)
   
### _2. Set up user.name + user.email_
    - git config --global user.name "<your GitHub username"
    - git config --global user.email "<your GitHub email"
   
### _3. Create a GitHub repository_
    - git clone URL
    (You can find your repo URL here)
    
   ![image](https://user-images.githubusercontent.com/73635652/101719305-a8d66500-3ad5-11eb-8228-208f58d38881.png)
   
    - git add .
    - git commit -m "you can write anything here"
    - git push
      
## **IV. How to resolve conflicts**
### _1. Create a conflict_
    - Create a new branch nbtest
    - Create a file  cf.txt
    - git add . -> git commit -> git push origin nbtest
    
### _2. Solve the conflict_
    - git checkout main
    - Create another cf.txt file
    - git add . -> git commit -> git merge nbtest
    
   **Git will report the conflict and ask which version of the file cf.txt do you want to choose**
   
    - Resolve conflict
    - git add . -> git commit -> git push
  
## **V. Branching**
