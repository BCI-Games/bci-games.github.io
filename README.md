# BCI GAMES Website

Welcome to the public code repository for BCI Games. A company that helps developers integrate Brain Computer Interfaces into their video games and provides families and individuals with paralysis or motor disabilities resources and access to BCI enabled video games. BCI Games is created by developers and researchers and our site is open source to allow for those who notice a bug to make changes.

## How the site works
This website is statically generated. Everytime a code change is made to the development branch, github actions will clone the repository and build the entire website and pull our discord sesh events and publish the results to our master branch to be served using Github Pages. This keeps operating costs at a minimum while ensuring the website remains secure.

## How to Develop Locally

Developers and learning programmers are free to clone this repository and create a new branch to make code changes and learn about how our site works.

**Pre-Requisites**
- Jekyll
  - [Windows Installation Instructions](https://jekyllrb.com/docs/installation/windows/)
  - [Mac Installation Instructions](https://jekyllrb.com/docs/installation/macos/)
  - [Ubuntu Installation Instructions](https://jekyllrb.com/docs/installation/ubuntu/)
- Once installed then type the following command in your terminal. ```gem install jekyll bundler```

**Site Development**

1. Clone the repository to your computer (you can use github desktop if you're not familiar with Git CLI)
2. From your terminal (powershell, windows term, iterm, cmd, etc...) navigate to the root of the project directory ```cd /Folder-Path-To/ExtraLifeYYC.github.io/```
3. Then type the following command in your terminal to install the gems and plugins required to build the website properly ```bundle install```
4. Now you can build the site by typing in the command ```bundle exec jekyll serve ```
5. Open a web browser and go to http://localhost:4000 to see the site.

To make development easier use ```bundle exec jekyll server --livereload``` the site will automatically rebuild when you make changes to the code in the repo. 

*(Warning: Livereload will not work out of the box on Windows [visit this link for instructions to fix --livereload](https://robbinespu.gitlab.io/blog/2020/10/16/jekyll-unable-to-load-the-eventmachine-c-extension/))*


**Submitting Code Changes**

Before making changes to the code, be sure to create a branch in your code repository (if you don't know what a branch is, watch this [video about branching](https://youtu.be/QV0kVNvkMxc) ). Once all of your code changes in your branch are done, stage and commit them, then make a pull request to development.

One of the Repository admins will review your pull request and if the code/feature you add is good, we will merge in the request. If we find a problem with the new feature or change you've made we will reject the request and leave a comment about why it was rejected.

## Other Ways to Help

If development is not your jam, just drop us a line saying hello. We are always looking for volunteers. If you are an artist, writer or creative type interested in Brain controlled gaming please contact us, as we have lots of developers looking for creatives. Email us a contact@bci.games