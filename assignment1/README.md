# Getting Started with git
This assignment will go over the `git` commands and workflow we covered in lecture. The workflow is laid out for you step-by-step, but the exact commands are not given to you upfront--feel free to use google, git cheatsheets, class notes, etc. to help you through this. The more you use the `git` workflow, the more you'll remember the common commands. 

## Assignment
You will be creating a "feature" in this repository, which will consist of you adding a file to this repository containing basic information about yourself using the feature-branch workflow. 

### Part 1
* Clone this repository to your `local` machine. By default you are on the `master` branch.
* Create a new branch (off of master) to implement your feature. *Name this branch in a descriptive way.* Example branch names: `add-new-button` `sk/add-submit-button`, `sk317/update-readme-links`. Note that often times a personal identifier (like `sk` or `sk317`) is added in front of your branch name.
* Create and **commit** an empty file called `info.csv` to your branch. Be sure to have a [good commit message](https://chris.beams.io/posts/git-commit/#seven-rules).
* Now populate `info.csv` with a single line that contains your `first_name, last_name, netid, full_duke_email, github_username` in a comma seperated format:
  ```csv
  Suyash, Kumar, sk317, suyash.kumar@duke.edu, suyashkumar
  ```
* Commit this change to your feature branch
* Push your `local` branch to the default `remote` (called `origin`). 
* You should now be able to see your branch on Github (which is the `remote` in this case)
* On GitHub, create a "pull request" to have the new feature branch merged into the master branch.
Then, accept the merge. 
* On your local computer, check out the `master` branch and then pull the newly merged `master` branch to your local repository.

### Part 2
Your task for Part 2 is to edit this README to add an image of your favorite plant or animal. Don't forget about the Markdown cheatsheet [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to learn more about syntax for adding images.
* On your local copy of the repository, create a feature branch to complete the task of adding an image of your favorite plant or animal to this README. Be sure to name the branch well as described above.
* In README, create a new heading with an appropriate title
* Add a short description of your image.
* Add a picture to the README file.
* Commit your changes to the feature branch and push it to GitHub.
* Make sure that your image is shown effectively on the new feature branch in GitHub.  If not, make the needed changes to the README file either a) locally on your computer and push them to GitHub, or b) make the changes directly on GitHub.
* On GitHub, create a "pull request" to merge the new feature branch into the master branch and complete the merge.
* On your local computer, remember to check out the `master` branch and then pull the newly merged `master` branch to your local repository.


**This image below is my favourite animal, as required in assignment 1:**
![alt text](https://github.com/YeTian-tech/BME-547/raw/master/Assignment1_image.jpg)



