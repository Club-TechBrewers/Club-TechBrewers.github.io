# How to make your first pull request on GitHub

>## What is forking?
```text
When we love someone’s repository and would like to have it in our GitHub account, we fork it so that we can work with it separately.
When we fork a repository, we get an instance of that entire repository with its whole history. After forking, we can do whatever we want to do without affecting the original version.
```
>## What is a pull request?
```text
Pull requests are the way we contribute to group projects or open source projects.
For instance, a user Harry forks a repository of ThanoshanMV and makes changes to that repository. Now Harry can make a pull request to ThanoshanMV, but it’s up to ThanoshanMV to accept or decline it. It’s like saying, “ThanoshanMV, would you please pull my changes?”
```
>## What it means to contribute?
```text
Not only can we contribute to an open source project with code, but we can also contribute in many other ways. Some of these ways are described below.
We can contribute to an open source project in the following ways:

1. Designing: You can construct the layouts of a project to improve its usability, improve the project’s navigation and menu based on user research programs, create art for logos or t-shirts, and provide style guides for the project.

2. Writing: You can write and improve the project’s documentation or translate the documentation, start a newsletter for the project or write tutorials for the project and curate highlights from the mailing list, or curate a folder of examples showing how the projects are used.

3. Organizing: You can link duplicate issues, suggest new issue labels, suggest to close old open issues and ask questions on recently opened issues to move the discussion forward.

4. Help others: Answer questions on open issues, review code on other people’s submissions and offer to mentor another contributor.

5. Coding: Help solve any open issues, ask if you can provide any new features and improve tooling and testing.
```
>## Let’s make our first pull request!

### If you’re not very familiar with Git & GitHub, please check out this [session](https://www.youtube.com/watch?v=t9X_PDOJyCI).

```text
1. Fork the repository
Fork the repository by clicking the fork button on the top of the page. This will create an instance of that entire repository in your account.
```
![image](https://user-images.githubusercontent.com/74014564/195529456-1e5cedc1-e35a-4c36-bfad-56a8e34981f6.png)

```text
2. Clone the repository
Once the repository is in your account, clone it to your machine to work with it locally.

To clone, click on the clone button and copy the link.
```
![image](https://user-images.githubusercontent.com/74014564/195530330-e3634931-fcba-4bb2-9c2c-a63f716a3804.png)

### Open the terminal and run the following command. It will clone the repository locally.

```bash
$ git clone https://github.com/Club-TechBrewers/Club-TechBrewers.github.io.git
```
### We need to go to that cloned directory by running this command:
```bash
$ cd /Club-TechBrewers.github.io
```
```text
3. It’s good practice to create a new branch when working with repositories, whether it’s a small project or contributing to a group's work.

Branch name should be short and it should reflect the work we’re doing.
```
### Now create a branch using the git checkout command:

```bash
$ git checkout -b [Branch Name]
```
```text
4. Make essential changes to the project and save it.

Then execute '$ git status', and you’ll see the changes.
``` 
### Add those changes to the branch you just created using the git add command:

```bash
$ git add
```
### Now commit those changes using the git commit command:
```bash
$ git commit -m "Enter your commit message here" 
```
```text
5. Push changes to GitHub
In order to push the changes to GitHub, we need to identify the remote’s name.
```
```bash
$ git remote
```
### After identifying the remote’s name we can safely push those changes to GitHub.