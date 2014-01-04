Welcome
=======

All members are requested to add their name in this repository to get push access to all pulug repositories. This repository can be used to practice your first pull, commit, push. 

Due to the way in which github works you need to first fork this repository, push your commits to your fork and then submit a pull request on the website.  

Steps: 
- - - -

1. Click fork button on the top right corner  
2. Go to your fork and find the cloning address in the right side panel  
3. In your terminal type  
      `git clone https://github.com/UserName/members.git`  
4. Go in the cloned repository i.e _members_ folder in the current directory  
      `cd members/`  
5. Open the [list.txt](list.txt) file and save your name, email etc. in it 
      `vim list.txt` or  
      `gedit list.txt` or  
      `kate list.txt` or  
      `xdg-open list.txt` or whichever editor you like.
6. Use following command to add your changes for the upcoming commit 
      `git add list.txt` 
7. Commit __all__ your changes using the following command  
      `git commit -a`  
    _Note: `git commit -a` stages all your changes whether or not you used `git add` for them._
8. Edit the commit message to clearly **describe** your changes and __save__ it. 
9. Now if everything went well, you should probably see your commit message in the `git log`.  
10. Use following command to push your changes to your forked repository online  
      `git push origin master`  
11. Now open your browser again and submit a pull request using the pull request tab/option on the right hand side  

* * *

Follow these steps and send that pull request to start contributing :)  
Good Luck ! ! !  

Links:   
[More about git](http://www.developfreedom.com/2014/01/git.html)  
[.gitconfig file](https://github.com/shubhamchaudhary/dot/blob/master/.gitconfig)  
[git-scm](http://git-scm.com/)  
[PULUG](https://groups.google.com/forum/?fromgroups#!forum/pulug)   
