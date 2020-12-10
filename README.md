# Code Refactor

I've started this project to help better understand what my day to day work will be like once I'm in the field. Here I've been given a set of HTML and CSS with some errors in them. I will go through step by step of how I fixed these errors and gave the wedsite a live URL.

## Steps For Giving The Webite A Stand Alone URL
1. Open Github.com
2. Open the repository for project
3. Open the settings link
4. Scroll down towards the bottom till you see "Git Hub Pages"
5. Set your URL through github using your github username and the name of the project.
6. Click to add a "README.md file"

[github screenshot](assets/images/github-pages.png)


## How To Get The "Search Engine Optimization" Link To Work
1. I notice the "Search Engine Optimization" line of code was set to an id but was labeled as a class in the link text.
2. Simply changing the code over from class= to id= did the trick.

## Combining CSS Properties For The Class For Benefit
1. Combine the class for benefit-lead h3, benefit-brand h3, benefit-cost h3 to benefit-all h3
2. Combine the class for benefit-lead, benefit-brand, benefit-cost to benefit-all
3. Combine the class for benefit-lead img, benefit-brandimg img, benefit-cost img to benefit-all img
