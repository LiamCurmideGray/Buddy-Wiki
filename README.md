# Hello GAPT Buddy Collaborators!

This small wiki will be a guide on how to push your files and code to our communal repository.
Kindly treat this wiki as a Bible (or sorts) so that there will be very little to none wrong pushes.

### Summary on Github
Github is a cloud File Structure system where you are able to store all your files on the cloud that fall under a repo (like this one!)
Once a repo is created you're able to copy it to your local machine (i.e cloning it) and you'll be able to gain access to all the files stored on the cloud (at the time of cloning it, kind of like a snapshot). From there you're able to add new files and send them back (i.e PUSH) to the cloud repo where it'll be updated and your other collaborators are able to PULL the new added files to their local devices and everyone can continue on their development in a smooth transition. 

The added benefit for Github is that when you upload a code file, it's able to recognise new changes happen to it and update them accordingly!

*** 

### Terminologies 
In this tutorial I'll be using a couple of Terminologies that work in practise with Github here are their definitions:

* `REPO` ~ This is the cloud file structure (i.e here on Github.com)
* `CLONE` ~ Taking a copy of the latest files in the repository (kind of like a snapshot) and storing them on your local machine
* `FETCH` ~ Checks if there's anything new from the repo
* `PULL` ~ Pulls down the files from the repo
* `STAGE` ~ Select which files you want to PUSH back to the repo
* `COMMIT` ~ Wrap the selected staged files under a package that's ready to be sent back to the repo
* `PUSH` ~ Push your wrapped commit to the repo
* `MAIN` ~ This is our main branch where all the files will eventually come on this lane 
* `BRANCH` ~ You're literally branching off to the side and creating a new lane where eventually you'll come back to your main branch
* `PUBLISH` ~ You're pushing a blank branch so the repo is able to recognise that a new branch exists
* `PULL REQUEST` ~ You're trying to push your new added files to the branch & requesting your collaborators to review in order for them to approve your request and pull it to it's respective branch.
* `CONFLICTS` ~ Oh boy.... There are 2 of the same files that have different code in the same lines, you should better fix that! 
* `MERGE` ~ Your pull request has been approved and has successfully been merged into the repo.
* `.GIT IGNORE` ~ You'll notice this file once downloaded on your local device. This is a special file which can be edited to NOT allow specific files to be added to the repo if needed.
* `SWEAR` ~ You'll be doing that a bunch

***

### Our Branch Structure

The branch structure has 3 primary lanes, the main which is where both groups code & files come together and each of their respective team branch where from there you're able to create a third branch per person for any feature you want to implement. Once teams have reached a milestone they should merge it into the main branch for everyone to be able to utilize it. You can find the structure below.

Our branches (lanes) 
1. main 
   1. Front-End
      1. Feature
      1. Feature
      1. etc..
   1. Back-End 
      1. Feature
      1. Feature
      1. etc..

***

### RULES TO ALWAYS REMEMBER
1. THE MAIN BRANCH SHOULD ALWAYS BE IN WORKING CONDITION
1. NEVER EVER WORK OR PUSH DIRECTLY TO THE MAIN BRANCH, ALWAYS BE WORKING ON A FEATURE BRANCH YOU CREATED
1. WHEN ABOUT TO PUSH YOUR CODE MAKE SURE AT FIRST YOU ALWAYS SELECT YOUR FEATURE BRANCH AND NOT THE MAIN BRANCH
1. NEVER HAVE 2 PEOPLE WORK ON SEPERATE BRANCHES ON THE EXACT SAME FILE, THIS IS THE CAUSE OF CONFLICTS
1. THE MAIN BRANCH IS VERY VOLATILE AND CAN BE BROKEN EASILY IF NOT CAREFUL!!!!!!!

***

## Tutorial
Here I'll actually start providing the guide on how to pull and push to the repo successfully. (Keep this wiki open anytime you're trying to work with the repo. I'll be using images on Git Desktop (this should be installed already on your local machine) to help explain easier. You can use different application like Git Extensions or Git Kraken (in concept this guide will still work if you're using a different application but may adjust some extra tweaking). 

### 1. Cloning the repo

For starters it's time to clone the repo to your local device. Got to the main home page of the repo, click the green Clone button and then click the button that says Open with GitHub Desktop.

![Clone Repo](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Home%20Page%20-%20Cloning.PNG?raw=true)

Once Github Desktop opens you'll be presented with a screen where you want to store the repo at which directory, you can choose it where ever you want.
Keep in mind if you've already started working and have files I will come to that in next steps on what to do.

![Clone Repo Github Desktop](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Clone%20Repo%20Github%20Desktop.PNG?raw=true) 

### 2. Github Desktop Fetching & Pulling

Welcome to Github Desktop, to get you started, you should first click FETCH button to see if there are any updates from the repo. If there are the fetch button will turn into pull and you can download the latest code on the main. This small step is very important and should be done every time you end up on the main branch. 

![FETCH from main](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Fetch%20from%20main.PNG?raw=true)

The number next to the Pull refers to how many commits there have been.

![PULL from main](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Pull%20from%20Main.PNG?raw=true)

### 3. Moving through the branches 

Select the branch and go into your respective team branch.

![Git Dashboard](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Desktop%20Dashboard.PNG?raw=true)

Once in your respective team branch, click again fetch and pull to get all the data onto this branch (this might happen automatically but you should still do it just in case it misses something). Then click again branch and select create a new branch.

![New Branch](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/New%20Branch.PNG?raw=true)

By default GH Desktop will ask you from which branch you want to branch off from, select your team branch. NEVER from main branch. Give it a name of the current feature you're going to be working on. Then click create branch.

![Team Branch select](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Team%20Branch%20Select.PNG?raw=true)

Then select Publish Branch in order for the repo to recognise a new branch has been created.

![Publish Branch](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Publish%20Branch.PNG?raw=true)

### 4. Adding new files

From here you're now able to create and add new files to your local directory.

NOTE: This is the point if you have worked on stuff already, now is the time to gather all your files and place them in the same directory where you have stored the cloned repo. You can click from the top Repository then Show in Explorer to open the folder where all your files are saved at.

![File Explorer](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/File%20Explorer.PNG?raw=true)

Once adding new files or changes, you'll start notices the changes made on your Github Desktop

![New changes](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/New%20Changes.PNG?raw=true)

NOTE: Features should be relatively small in terms of coding say a max of 3 methods/functions, don't try add a 1000 lines of code in 1 go as your teammates will need to review your changes. More on this in the later steps. 

### 5. Commits

Once satisfied with your additions you're now ready to commit. You'll need to give your commit a title and optional a description, this will help the reviews have an understanding of what you're going to try and push.

![Create Commit](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Create%20Commit.PNG?raw=true)

Once committed you'll notice a Push button appear. Push it to the repo.

### 6. Pull Request

Go onto the website and look up the repo, on the main page you'll notice a new Pull Request wants to be created. Select compare & pull request.

![Compare & PR](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Compare%20&%20PR.PNG?raw=true)

The first thing you'll notice it the your commit title & description has been retrieved. BEFORE CLICKING CREATE PULL REQUEST. Change the base from main branch to your group branch. DO NOT LEAVE IT ON MAIN BRANCH, I WILL KNOW!  

![Rebase to Group Branch](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Rebase%20to%20Group%20Branch.PNG?raw=true)

Once you have rebase to your group branch, you're able to select Create pull Request.

### 7. Reviewing

Congratulations you've successfully created a pull request! On this screen you're able to view the title of the commit & description, the files added / changed / removed, and lastly the merge button which by default will remain locked off at the moment. From here you'll have to contact your colleagues in order to review and approve of your changes (minimum of 2 people and no yourself doesn't count as 1 of them).

Note: I can only show you my only Admin privileges which would let me bypass this rule. Yours would look a little different from the picture displayed.

![Open PR](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Open%20PR.PNG?raw=true)

To review the changes, your colleagues should be able to view a green button that says Review Changes. If you can't find it on this page, select the Files Changed tab and you will definitely find it there. On this tab you'll be able to get an extensive look at the code and also approve of the changes. Reviewers have the capabilities to leave comments on the whole file or even comments on specific lines of code.

NOTE: Kindly try to take a small effort and understand your colleagues work in order for everyone to remain on the same page at the direction of where the project is going. 

Once you have received enough approvals you're able to merge it into your respective branch. 

NOTE: This is where the potential of conflict can appear, if you ever run into this, kindly contact me to help you resolve it. 

![Review Changes](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Review%20Changes.PNG?raw=true)

### 8. Deleting your feature branch 

Once successfully merged, you'll be given the option to delete your feature branch from the website repo, kindly do so as you don't require your branch any longer. 

![Delete Branch Remote](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Delete%20Branch%20Remote.PNG?raw=true)

From your Github Desktop, you should also delete your feature branch. This can be done by still being on your feature branch on your local device, selecting branch at the very top and then selecting delete. If a pop up shows up claiming that it's still on the remote repo, tick it and delete the branch.

![Delete Branch Local](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Delete%20Branch%20local.PNG?raw=true)

### 9. After Merging

You'll notice that on the home page, you're group branch wishes to create a new pull request that will get added to the main branch. Only create this pull request once you have a sufficient amount or collectively agreed as a group when pushing to the main branch. REMEMBER: THE MAIN BRANCH SHOULD ALWAYS BE WORKING.  

![Group PR](https://github.com/LiamCurmideGray/Buddy-Wiki/blob/master/Github%20Wiki%20Images/Group%20PR.PNG?raw=true)

### 10. Repeat

Congratulations on successfully pull and pushing into the repository, from here start over from STEP 2 and the cycle repeats on and on.

***

### Conclusion

Hopefully this guide helps you well, if you have any queries or didn't understand a step, feel free to ask me

Thanks <3 

# **Liam Curmi de Gray**

***
