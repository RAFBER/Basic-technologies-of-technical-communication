---
layout: default
title:GitHub
nav_order: 3
---

# How to work with GitHub
{: .no_toc}


![GitHub logo](/assets/images/GitHub_logo.jpg)

- [How to work with GitHub](#how-to-work-with-github)
- [1. What is GitHub?](#1-what-is-github)
  - [What is the Git, GitHub and GitHub Desktop Client?](#what-is-the-git-github-and-github-desktop-client)
- [2. How to create an account on GitHub?](#2-how-to-create-an-account-on-github)
- [3. GitHub Desktop Client](#3-github-desktop-client)
- [4. Working with GitHub](#4-working-with-github)
  - [4.1 Creating a new repository](#41-creating-a-new-repository)
    - [4.1.1 Creating a new repository in GitHub Desktop Client](#411-creating-a-new-repository-in-github-desktop-client)
    - [4.1.2 Creating a new repository on the GitHub server.](#412-creating-a-new-repository-on-the-github-server)
- [4.2 Working with the files](#42-working-with-the-files)

# 1. What is GitHub?
* GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

* It was created by Linus Torvalds.  
* The files "live" locally on our computer, and their copy on
the GitHub server, from where we can share them with other GitHub users.
* If we work in a group, everyone can have their own files version called
**branch**, which it can then incorporate into a shared version (operation
joining is called **merge**). Branches are also useful for solo work, when we're working on a draft version and then we include it in the official version.


## What is the Git, GitHub and GitHub Desktop Client?
Git is a distributed version control system. This is a tool, conception.  
GitHub is a cloud-based hosting service that lets you manage Git repositories.  
GitHub Desktop Client is a special application to menage the content on the GitHub server from local PC.

To work with GitHub you need to create an account on it.

# 2. How to create an account on GitHub?

* Go to https://github.com/ and click *Sign up for GitHub*.  

  ![GitHub sign up](./GitHub_01.jpg)

* Enter your *Username*, *Email address* and *Password*. Verify that "you are not a robot" and click **Create account** button. You can change the user name and password later on.

  ![GitHub sign up](./GitHub_02.jpg)

* In the next step mark your preferences and the correct topics what you're interested in and click **Complete setup**. You will be asked to verify your email address. 

  ![GitHub sign up](./GitHub_03.jpg)



* Go to your mailbox and click on the link sent by GitHub. Your account is ready to work now. In next step or later on you can complete your profile if you want, add the profile picture, etc.

* Helpful links: 

  [GitHub guides](https://guides.github.com/activities/hello-world/)

  [GitHub Help](https://docs.github.com/en)

  [Video tutorials](https://www.youtube.com/githubguides)


# 3. GitHub Desktop Client

To work with GitHub hosting service you should install also the GitHub Desktop Client on your PC.  
To installation instructions of the GitHub Desktop Client go to:  
[GitHub Desktop Client installation](GitHub_Desktop_Client.md)


# 4. Working with GitHub

## 4.1 Creating a new repository

It can create a new repository in two ways:  
Locally in the Github Desktop Client application and directly on the GitHub server.

### 4.1.1 Creating a new repository in GitHub Desktop Client

* File tab> New repository.

  ![GHDC new repository](./GitHub_04.jpg)

* The following dialog should appear:

  ![GHDC new repository](./GitHub_05.jpg)

  Enter the repository name, description and choose the path in your PC. The path should be as short as possible. Mark the field *Initialize this repository with a README* (a README file will be created) and click **Create repository**. The *Git ignore* and *License* fields should be marked as "None".

* The new repository has been created in your PC. You need to publish your repository on the GitHub server. Click the **Publish repository** button.

  ![GHDC new repository](./GitHub_06.jpg)

* The following dialog should appear:

  ![GHDC new repository](./GitHub_07.jpg)

  Choose the GitHub.com tab. Mark the field *Keep this code private* if the repository should be available only for you. You can change this option later to give the access to your repository for other GitHub users. Click the **Publish repository** button.

* Check the GitHub server. The new repository should appear in your GitHub account. Refresh the page if is not visible.

  ![GHDC new repository](./GitHub_08.jpg)

### 4.1.2 Creating a new repository on the GitHub server.

You can create a new repository directly on the GitHub server as well. To create it proceed as follows:

* Click the **New** button on the main screen in your GitHub account.

  ![GitHub server](./GitHub_09.jpg)

* Enter the repository name. Decide that the repository should be *Private* or *Public*, mark the *Add a README file* field and click the **Create repository** button.

  ![GitHub server](./GitHub_10.jpg)

* The new repository has been created. The following screen should appear:

  ![GitHub server](./GitHub_11.jpg)


  At this moment your repository exist only on the GitHub server. You need to clone it into your PC. 

* Click the **Code** button (1) and choose the *Open with GitHub Desktop* option (2).

  ![GitHub server](./GitHub_14_2.jpg)

* The following dialog should appear:

  ![GitHub server](./GitHub_15.jpg)

  Click the URL tab. Choose the location for your created repository and click the **Clone** button.

* Your new repository should appear in *Current repository* tab in the GitHub Desktop and new folder should be created in the indicated location.

  ![GitHub server](./GitHub_16_1.jpg)

  ![GitHub server](./GitHub_17_1.jpg)


  You can also create a new repositories from other place in your account on the GitHub server.

* In your profile main screen click the *Repositories* (1) and the **New** button (2) later on.

  ![GitHub server](./GitHub_18_1.jpg)

* You can also create a new repository by click the **Start a project** button on main GitHub screen (you must be logged in).

  ![GitHub server](./GitHub_19.jpg)


  In either case, the procedure for creating a new repository is the same.

# 4.2 Working with the files





