# A03


**Github** 

**Github** is a website that manages user code using **git**, a open source version control software. The **repository** is where your code is stored. Both locally and online in a **remote** repository. To bring the remote repository you will need to first **clone** or copy it onto your local machine. 

When you want to update your local repository later on if the remote repository is updated there are two ways to do so. Either **fetch** the changes from the remote repo and then **merge** it, as in combine the new code with the code that's already there. OR you can **pull** and that will fetch and merge it all at once.

When you want to add changes to the remote repo, you can add files to a commit, and then **push** it which will merge the code from your local repo with the remote repo. 

Other things to note. You can make new **branches* to test stuff with code, so if you are working on something and it doesn't entirely work, you can make a new branch and push to that branch until its finished, then merge the new branch with the main branch, or the main code. 

Unfortunately at times when code can get messy **merge conflicts** occur, which usually happens when two people try to modify the same files, git will throw a flag asking how it should handle the competiting code. In order to resolve the conflict you go into the code and decide what lines of code stay and what needs to go.


**With Downloading Webstorm**

Go to https://www.jetbrains.com/community/education/#students 

Apply for the student license using your school Id

After having your license there will be various links to all the jetbrains products you have access to, navigate to the link that says webstorm and download it. 

After downloading it, open up your system preferences and go to version control. Here is where you will link your git download on your local machine. Then you will need to login with your passwords, so that webstorm and directly modify your remote git repository. I think though that's deprecated now, and now you need to use github generated tokens in place of passwords which you assign the permissions the software has. Finally you create a repo on github, then go back into the version control settings on webstorm and link the 2 together.
