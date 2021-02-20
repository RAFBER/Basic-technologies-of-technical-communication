---
layout: default
title: Working with branches
parent: GitHub
nav_order: 3
---

# Working with branches
{: .no_toc}

## Table of contents
{: .no_toc}

1. TOC
{:toc}

The general idea of work with branches in GitHub is that the developer makes some changes does not make changes to the main branch but into his branch. Then the changes are committed and merged into the main branch.  
The developer works without ane affect to main code base.  
The great advantage of such work is that the main code base is error-free because changes to the main code base are merged only after approval by the editor.  
Use a branch always if you would like to isolate your work without affecting to other branches in the repository.

## Basic work flow of GitHub branch

   ![Files structure](../assets/images/GitHub_Branch_Workflow.svg)


# How it works?

## Review process

* Choose your repository you want to make a branch and click the **Settings** button.

   **Note:** The repository you work on must be "Public".

   ![Branches](../assets/images/Branches_1.png)

* Choose the *Branches* from the settings menu.

   ![Branches](../assets/images/Branches_2.png)

* Go to section *Branch protection rules* and click the **Add rule** button.

   ![Branches](../assets/images/Branches_3.png)

* Type the branch name (1) (should be the same as default branch) and mark the option *Require pull request reviews before merging*. That is means that any changes in your branch need your approval. Click the **Create** button.

   ![Branches](../assets/images/Branches_4.png)

* Click the **Save changes** button.

   ![Branches](../assets/images/Branches_5.png)

* Go to the *Manage access* option in menu and invite a collaborator to work on your repository. The procedure invitation of collaborator is described in *GitHub - the basics*, chapter *Making the repository available to other users*
* In the next step the collaborator needs to clone repository from your GitHub account. The repository clone procedure is described in *GitHub - the basics*, chapter *Creating a new repository on the GitHub server*

* After the repository clone the collaborator needs to create a new branch in his PC using the GitHub Desktop. 

* In the proper repository (1) in the *Branch* tab he needs to choose the *New branch* option.

   ![Branches](../assets/images/Branches_6.png)

* He should name the new branch (1) and click the **Create branch** button.

   ![Branches](../assets/images/Branches_7.png)

   The new branch exist now only in collaborator PC. He should Publish branch into repository by click thr **Publish branch** button.

   ![Branches](../assets/images/Branches_8.png)

* Now exist two branches in repository.

   ![Branches](../assets/images/Branches_9.png)

* By click on it the details of the creating branch are visible.

   ![Branches](../assets/images/Branches_10.png)

* After the changes implemented in file he work on he should make a commit and Push origin AND THEN MAKE A *Pull request* by click the **Create pull request** button.

   ![Branches](../assets/images/Branches_11.png)

* In the next step he need to type a comment (1), choose a reviewer (2) and click the **Create pull request** button.

   ![Branches](../assets/images/Branches_12.png)

* The following window should appear:

   ![Branches](../assets/images/Branches_13.png)

   Review is required (1) because you have marked this option during adding the rules to the branch and merging is blocked (2) till you accept the changes.

* The *Pull request* is visible now into your account. Click on it.

   ![Branches](../assets/images/Branches_14.png)

*   You have also received the message by email informing you about the changes.

    ![Branches](../assets/images/Branches_15.png)

* Click on the file that has been changed.

   ![Branches](../assets/images/Branches_16.png)

* You have information about *Commits* (1) and files changed (2). Click the **Add your review** (3) button.

   ![Branches](../assets/images/Branches_17.png)

* You can check the changes (1) now. Click the **Review changes** (2) button, mark the *Approve* option (3) and click the **Submit review** (4) button.

   ![Branches](../assets/images/Branches_18.png)

* The merging is possible now. Add the comment in comments field if you want and click the **Merge pull request** button.

   ![Branches](../assets/images/Branches_19.png)

* Confirm merge.


   ![Branches](../assets/images/Branches_20.png)

* You can delete the branch if you don't need it anymore. 
  
   ![Branches](../assets/images/Branches_21.png)

* Your collaborator should delete this branch in his GitHub Desktop.

   ![Branches](../assets/images/Branches_22.png)

Learn more about GitHub branches

[GitHub branches](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches)
