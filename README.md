[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/RbaYQTOJ)
# Lab 5 - Data Exploration Blog with Analytics

WARNING: This repo is a website that is hosted online by GitHub. The outside
world can see this website, so please keep that in mind as you add
content, write commit messages, etc.

- [Starter Repo for reference](https://github.com/allegheny-college-cmpsc-105-spring-2024/lab05-resto-starter)
- [Website url](https://allegheny-college-cmpsc-105-spring-2024.github.io/lab05-resto-starter/)

## Learning outcomes

After completing this lab, you should be able to:

- describe Google Analytics
- read information from dashboards
- identify different sources of data
- navigate the directory structure in the project
- contribute to web docs online

## stepss

Summary of stepss. Details are below

0. steps: in GitHub, go to settings>pages (you can add /settings/pages to the url)
   Under branch, click  `main` and then `save`. Refresh after 30 seconds to get live link!
1. steps: Clone your repo using git, and open the project in Spyder
   following steps from last lab
2. steps: Add analytics to the site
3. steps: Submit work to GitHub using git
4. steps: Update this website with content!
5. steps: Submit work to GitHub using git
6. steps: Review your colleagues' restaurants/sports sites and write two short reviews
7. steps: Submit work to GitHub using git
8. steps: Check your analytics and make an additional post about the meaning of the data you see
9. steps: Submit work to GitHub using git

## How to clone your repo

- steps: in GitHub, copy the SSH link to your repo from the green `code` button
- steps: Open a terminal
- steps: `cd` to a location where you would like to store lab 5
- steps: type `git clone` then paste in the link
- steps: in spyder, open a new project from existing directory.
  - navigate to this lab and then hit create. You should then see all your files
    in the left hand panel. There are no code cells to run, but you can edit
    Markdown.

## How to add analytics to this website

- steps: in the `_config.yml`, add your Google Analytics tracking ID on line 5
- steps: submit your changes to GitHub
  - See below for `How to push your work onto GitHub`

## How to update this website with content

This website is for a restaurant that you would like to make or attend.
Come up with a concept for your restaurant. The concept does not have to be
realistic, but keep in mind that this website is viewable online.

- steps: fill out the `index.md` with a description of the concept of your restaurant
  - `index.md` will become the home page of the website automatically, so include
    information that you think belongs on the home page.
- steps: fill out the `menu.md` with at least one menu item and one photo
  - `menu.md` will automatically be linked in the website header for easy access.
- steps: fill out the `contact.md` with fake contact information for your restaurant
  - `contact.md` will automatically be linked in the website header for easy access.
- steps: submit your changes to GitHub
  - See below for `How to push your work onto GitHub`

## How to review another site

After Monday the 19th, look for `assigned review` document in Discord.
There you will find the websites that you need to review. Look at the sites and pretend
that you have eaten at that restaurant. In the `_explorations/review1.md` follow the
stepss and write your first review. In the `_explorations/review2.md` follow the stepss
and write your second review.

- steps: submit your changes to GitHub
  - See below for `How to push your work onto GitHub`

## What to do after the reviews are written

Visit the website of your reviewers and find one quote from each review of
your restaurant. Add these quotes to your home page! Gatorgrade will look
for quote syntax in markdown.

Also look at your analytics data. In `_explorations/analytics.md` write about the
different sources of data contributing to the analytics automatic dashboards.
If you were a real restaurant owner, explain how this information could help
you improve your business and why you came to your conclusions.

- steps: submit your changes to GitHub
  - See below for `How to push your work onto GitHub`

## How to push your work onto GitHub

- Open a terminal
- `cd` to the lab 5 directory on your computer
- type `git status` to see a list of files you have updated
- type `git add .` to "stage" your files
- type `git commit -m "message`
- type `git push origin main`
- type your ssh passphrase if requested
- wait approx 20 seconds and check GitHub Actions build status
- refresh your website page and check it out!

## Before the final submission

- Please check the gatorgrade report in GitHub Actions and resolve
  any issues, including completing and deleting all steps markers.
