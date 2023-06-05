# How to Use Github #### by Naomi

Welcome! Although I may not be the best source out there for all of your GitHub needs, I figured it would be helpful to make a straightforward how to guide for all of our new Harvard Forest users out there. There are plenty of sites that will walk you through this too, but they tend to be wordy and honestly, pretty boring. Hopefully I do a decent job at spicing things up and being straight to the point. 

Still have questions after reading this? Feel free to email me at nhegwood@college.harvard.edu or come find me! 

# What even is GitHub?
GitHub is a useful tool to share and collaborate with others on code. It also tracks and saves changes to your code files, making it easy to go back and see what edits have been made, when they were made, and by who. It's like the "See Changes" function in Google Drive, but for code. 

# How do I use GitHub?
Technically, you can use GitHub through the command line, but I honestly never really got the hang of that. The easier, more user-friendly way to use GitHub is through GitHub Desktop. 

GitHub Desktop looks like this:
<img width="1146" alt="Screen Shot 2023-06-05 at 8 53 21 AM" src="https://github.com/Harvard-Forest-Ecosystems/How-to-Use-Github/assets/70771598/c736264c-25a9-44e9-bad6-dc95c81f3aeb">

In the top left corner, it says your current repository. **Repositories** are basically folders of code files, just like a folder you may have on your desktop. You can make a repository by going to GitHub on a web browser, going to the organization you want to make it under, and finding the "Make Repository" button. You are actually in a repository right now if you are reading this guide off of GitHub! 

To the left of your current repository is your branch. **Branches** are a little complicated, but I will do my best here. In short, branches allow users to work on code without other users edits. Branches always need to be merged back to the main branch eventually. The biggest downside is that if you merge back to the main branch and someone else has made edits to the file on the main branch, you have to deal with conflicting edits. I have only worked on the main branch because I usually work on code by myself, but branches can be helpful to use if many people are working on code. If you are interested in using branches, feel free to ask me or look here: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches 

Underneath the Current Repository section are files with edits that are waiting to be uploaded onto GitHub. You can click on a file to view it and the edits that were made. For example, if I click on Lambir_statistics_2022, this pops up:

<img width="1139" alt="Screen Shot 2023-06-05 at 9 08 57 AM" src="https://github.com/Harvard-Forest-Ecosystems/How-to-Use-Github/assets/70771598/fdc8db8d-ac24-4f61-be1a-149c3c25379b">

I believe I may have deleted this file and started from scratch or I may have moved the file to a different folder. The red areas (in this case all of the lines) are lines that have been deleted. In cases where lines were added, they will be highlighted green.

To upload one of these files, first select the box to the left of the desired file name. The box will green with a checkmark in it once it is selected. Then navigate to the box below the file names. In the area that says "summary (required)" enter a summary of the edits. This should be fairly short like "minor edits" or "added blank calculation." If you have more details to add, you can add them in the description box. Once you are ready, you can press **commit** to blank (in this case, it says "commit to main" because I am on the main branch). Once committed, you have to **push** the files, which is basically uploading them to GitHub. To do so, click the button next to the current branch label on the top. On my screenshot, it currently says fetch origin, but in practice it will say push.

At the start of each coding session, it is best practice to go to GitHub desktop and **pull** your files. This means that the files on your desktop will be updated with the latest version that is on GitHub. So, if your RA coded while you were away, you can see their updated code right away. This also helps prevent two different versions of the same code file from existing, which will save you a headache later on. To pull, go to GitHub desktop and press the button that on my screen says "fetch origin." This is the same button used to push changes. If there is anything to pull, it will often say pull. 

# This is all great Naomi, but how to I even set up GitHub Desktop??
There are a few ways to go about this depending on where you are starting:

## 1. You already have made a repository on GitHub or would like to make a repository through the GitHub website
Make a repository on GitHub, if you haven't already. Feel free to add a ReadMe file to describe what your repository is for and put in any other relevant information. What you are reading now is an example of a ReadMe file. You can also make a repository through GitHub Desktop by following the directions below.

After the repository is made, open GitHub Desktop. Then click the box in the top right corner that says "Current Repository." A side bar should then come up as so:

<img width="1142" alt="Screen Shot 2023-06-05 at 1 00 56 PM" src="https://github.com/Harvard-Forest-Ecosystems/How-to-Use-Github/assets/70771598/749c799b-f463-4a2f-8ee3-b140eaa1dc29">

Then, click the "Add" button. This will bring up a dropdown menu of options. If the repository you would like to connect already exists, click "Clone Repository" and navigate to the repository you would like to work with in the pop-up box.

## 2. You want to make a repository through GitHub Desktop
Open GitHub Desktop. Then click the box in the top right corner that says "Current Repository." A side bar should then come up as so:

<img width="1142" alt="Screen Shot 2023-06-05 at 1 00 56 PM" src="https://github.com/Harvard-Forest-Ecosystems/How-to-Use-Github/assets/70771598/749c799b-f463-4a2f-8ee3-b140eaa1dc29">

Then, click the "Add" button. This will bring up a dropdown menu of options. Click "Create New Repository." A box will pop up asking for information, such as what you would like to name your repository. Fill these things out and click "Create Repository."


## 3. You have a GitHub repository on your local computer
To be honest, if this is your first time using GitHub, this should not apply to you. But for those of you curious:

Open GitHub Desktop. Then click the box in the top right corner that says "Current Repository." A side bar should then come up as so:

<img width="1142" alt="Screen Shot 2023-06-05 at 1 00 56 PM" src="https://github.com/Harvard-Forest-Ecosystems/How-to-Use-Github/assets/70771598/749c799b-f463-4a2f-8ee3-b140eaa1dc29">

Then, click the "Add" button. This will bring up a dropdown menu of options. Click "Add Existing Repository." Navigate to the repository file. This has to be a GitHub repository!!! Otherwise, it will just tell you that it's not a repository.

# Now that I'm all set up, how do I access my code files?
To access your code files, you first have to move them into your repository. You can do this in one of two ways. The first way is to simply drag and drop the files into the repository through your web browser. To do this, have the repository on GitHub open in your browser and drag the files in. Then, go to GitHub desktop and press the pull button to import them onto your local device. 

The second way is to add the files into the appropriate folder on your computer. When creating/adding a repository to GitHub Desktop, it will tell you where it is creating a folder for the repository on your computer. You can then navigate to that folder and move any code files you want in the repository into the folder. Then, you have to go to GitHub desktop and **commit and push** all of the files onto GitHub (Otherwise, they won't be saved on to GitHub).

# I don't remember where GitHub made my repository folder
No worries! Open GitHub Desktop. On the top bar click Repository. Then, click "Show in Finder" if you have a Mac or "Show in ?" if you have not a Mac. I think it should work about the same for other systems, but a quick Google search may be helpful if this isn't the case.

<img width="521" alt="Screen Shot 2023-06-05 at 2 26 15 PM" src="https://github.com/Harvard-Forest-Ecosystems/How-to-Use-Github/assets/70771598/f7c92224-fe07-4821-9c65-91ceef061ebb">



**Note: To have GitHub track your changes, you have to have all of your code files in the repository folder on your computer and edit only those files. If you have more than one copy of the code file on your computer and edit one that is located outside of your repository's folder, GitHub won't be able to see the changes.**


# Glossary
**Repository**: GitHub's version of a folder
**Branch**: An offshoot that allows you to make changes to code without other people touching it. Good for collaboration and fixing bugs.
**Commit**: Saving your edits. This is where you can add comments about the edits you made.
**Push**: Uploading your edits to GitHub.
**Pull**: Downloading the edits you or others have made to your local computer.


