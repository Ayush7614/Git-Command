# Git-Command

Git Commands for Learning Purpose

To start contributing, follow the below guidelines: 

**1.**  Fork [this](https://github.com/Ayush7614/Git-Command.git) repository.

**2.**  Clone your forked copy of the project.
```
 $ git clone https://github.com/<your_gihub_username>/Git-Command.git
```
**3.** Checkout into a new branch 

     $ git checkout -b <branch_name>

**4.** Make your changes to it

**5.** Add and commit your changes

     $ git add . && git commit -m "<your_message>"
     
**6.** Push Code to Github under your branch 

     $ git push origin <branch_name>   

## 📌 How to Update Your Github Forked Repository

**1.** Lists the remote connections

    $ git remote -v

**2.** Adding the remote reporitory 
    
    $ git remote add upstream https://github.com/Ayush7614/Git-Command.git
    
**3.** Fetching The Upstream Repository

    $ git fetch upstream

**4.** Finally Merging with Upstream Repository

    $ git merge upstream/master
