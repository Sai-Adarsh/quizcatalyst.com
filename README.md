# Catalyst Quiz Corp

## Source code of catalyst quiz corp (quizcatalyst.com); created in 2018

* Clone to local machine
  ```sh
      git clone https://github.com/Sai-Adarsh/appendly.blogspot.com/
  ```    
* If you want to contribute to this website, create a seperate and give a PR (pull request)  

## Forking and Cloning

Before you can edit any file on the repo, you must fork and clone it. A **fork** is a copy of the repository in your account. To **clone** a repo means to download it locally. Click the Fork button on the top right of this repo to fork it. Next, go to your copy of the repo and click the Clone button. Copy the url. Now open git and execute this command:

```
git clone [copied url here]
```

That should download the repo locally.

## Making branches

A **branch** is a parallel copy of the code. When we add new features to a project, we usually create a copy of the code and work on it. This is done so that the main working copy of the code is unaffected. In most GitHub repos, the master branch is the default branch. You should create a separate branch for every contribution you make. To create a new branch, execute this command:

```
git checkout -b [branch name here]
```

You should see the branch name change on the terminal prompt. Congratulations! You created a new branch.


## Editing files

Create a new text file in the [contributors](contributors/) folder with your github handle as the file name. This file should contain your name. A sample file [aryadas98.txt](contributors/aryadas98.txt) has been provided.

## Adding and commiting changes

To create a **commit** means to save your work. But before you commit, you have to **add** your work to the commit. To do so, execute this command from the project root:

```
git add *
```

This adds all files to the upcoming commit. Now, to create the commit run this command:

```
git commit -m "[commit message here]"
```

Write any message in place of the commit message. If the command runs successfully, you should have committed your changes.

## Pushing changes and submitting a Pull Request

After committing your changes, you have to upload them to GitHub. This is known as **pushing**. To push your changes, run:

```
git push origin [branch name]
```

Where branch name is the name of your newly created branch. This should upload your changes to *your* GitHub account. Now, you can propose these changes to the actual project. To do so, click on the **Pull Request** button on GitHub. Most of the fields should be automatically filled out for you. Click Create Pull Request. If everything went correctly, you should have created a pull request with your changes. Now it is upto the repo owner to **merge** these changes.
