#Github Introduction
Github Tutorial
    Git:

      => Version Control System.
      => It helps you keep track of code changes.
      => Git is used to collaborate on code.
      
    Github:

      =>Github is a web-based git repository hosting service.
      
    Github Alternatives:
    ~~~~~~~~~~~~~~~~~~~~
      => Bit bucket
      => Git bucket
  -Create an account for github
  
  -Crreate a repository named as "githubInfo"
  
  -Inside the "githubInfo" repository create a file as test1.txt

Install Visual Studio/ PHP Storm or any editor

Install Git

# githubInfo

Create a new folder in visual studio as "gitIntro"

To get the test1.txt file from githubInfo repository in "gitIntro" folder  

Open the directory where the folder is created in visual studio in command prompt and execute the following command

  => git
  
  => git config --global user.name "Enter username"
  
  => git config --global user.email "Enter email"
  
  => git clone https://github.com/yogapriya-star/githubInfo.git
  
  => cd gitIntro

Create a new file as test2.txt  in "githubInfo" folder from visual code  

Open the cmd prompt 

  => git status
  
  => git add test2.txt
  
  => git status
  
  => git commit -m "test2.txt file is created in "githubInfo" folder from visual code"  
  
  => git push origin main

Create a new file as test3.txt  in "githubInfo" folder from visual code  

Open the cmd prompt 

  => git status
  
  => git add test2.txt
  
  => git status
  
  => git commit -m "test3.txt file is created in "githubInfo" folder from visual code"  
  
  => git push origin main

If I supposed to delete the "test3.txt" file created in "githubInfo" folder from visual code then merge this changes in to git repository by using following steps:

  Open the cmd prompt
  
    => git status 
    
    => git add test3.txt
    
    => git commit -m "test3.txt file is deleted in "githubInfo" folder from visual code"
    
    => git push origin main

  Create a new file from github repository and it should be reflect in  "githubInfo" folder from visual code" or any modification from github repository then use this command
  
  Open the cmd prompt
  
    => git pull 
