BUILD WEBSITE - Imagine someone has already downloaded your resume, you can't update that
# Hosting your resume on GitHub pages

## Purpose
This README describes how to apply the strategies and protocols mentioned in Andrew Etter's book *Modern Technical Communication*. We will host a resume on GitHub pages using those strategies.

## Prerequisites
A resume formatted in Markdown will be required. If you do not know how Markdown works, a link to a Markdown tutorial is provided in "More resources" at the bottom.

## Instructions
Before we start with the steps, we should know why we are using GitHub and Markdown.
1. **GitHub**  
  Andrew Etter talks about using distributed version control in his book. The prominent reasons for that: better performance, easier concurrent work and allows offline work. If you have to change anything in your resume, you can just pull it, which basically means download it, and make the changes. When you feel you are done, you will have to make just one commit and push, which is just uploading the updated file. You can work on your files for as long as you want without having to worry about losing your internet connection.   
  How does it helps in concurrecy? You can have mulitple people make changes to your resume at the same time. Everyone can pull, make changes, and push to a different branch. Then you can check which one you would like and merge their branch with the main branch. Merging is just combining the content of both the files. Now, the benefits of using a version control does not just stop here. In case, you think someone else had made better changes to your resume, you can always revert back to your original changes and merge that with any other branch.

2. **Markdown**   
  As Etter says in his book
  > The entire point of lightweight markup is to make it easier to produce well-formed XML, and we need XML in order to build websites.   
  
  Markdown is one of the most popular markup language. Markup languages are like human-readable XML. If you want more people to contribute to your resume, using a markup language is the way to go. Again, a mardown tutorial is provided in the "More resources" tab, if you would like to delve more into the langauge.
  
Now, let's get started with the steps:
1. **Make a GitHub account**   
  * First and foremost, you will need a GitHub account. If you do not have one, you can click [here](https://github.com/) to create your account.
2. **Create a repository**    
  * Next step is create a repository in your account. This repository is like a folder which will have your resume.
  * While on your homepage in GitHub account, navigate to top right of the screen and click the plus icon. 
  * Select "New repository" from the dropdown menu. 
  * It will open a new page where you can choose the name, description and theme for your repository. This page also asks you if you want to the repository to be public or private.
  * Once you are done filling in the details, click "Create Repository" at the bottom of the page.  
3. **Add a file**  
  * Open a repository and click on "Add file" at the top.  
  ![Add a file](https://ibb.co/whFs8X4)
