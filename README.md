# R-Ladies DC Git and GitHub Workshop <img src="img/rladies.png" align="right" width=200/>

## Slide Deck

[PDF Presenation Slides](https://github.com/rladies/meetup-presentations_dc/blob/master/GitHub-Workshop-2018/GitHubWorkshop-SlideDeck.pdf)

## Activities for Today

- [Create a GitHub Account](https://github.com/)
- [Install/Configure Git](https://github.com/kellobri/rladies-dc-github-wkshp#install-git)
- [Interact with GitHub Issues](https://github.com/kellobri/rladies-dc-github-wkshp#github-issues)
- [Make a Pull Request (on this repo)](https://github.com/kellobri/rladies-dc-github-wkshp#make-a-pull-request)
- [Create a Git Repository for an R project](https://github.com/kellobri/rladies-dc-github-wkshp#create-a-git-repository)
- [Practice: Push and Pull work from your repository](https://github.com/kellobri/rladies-dc-github-wkshp#practice-push-and-pull-workflow)
- [Knit/Render Rmd as github_documents](https://github.com/kellobri/rladies-dc-github-wkshp#knitrender-rmarkdown-for-github)
- [Make a Github Page](https://github.com/kellobri/rladies-dc-github-wkshp#github-pages)

### Resources

- Bookdown Reference: [Happy Git with R (Jenny Bryan)](http://happygitwithr.com/)
- Video Workshop (2017): [RStudio Git/GitHub Workshop (Jenny Bryan)](https://www.rstudio.com/resources/videos/happy-git-and-gihub-for-the-user-tutorial/)

### Tooling

If setting up git isn't an option on your local machine or if it's already configured for a different remote, you can set up a free [RStudio Cloud](https://rstudio.cloud/) instance to use for the purposes of this learning workshop. Create a free account by signing in with your GitHub profile. 

## Basics

### Install Git

Check to see if you have git installed on your machine. In some shell/terminal, run:
```
which git
git --version
```

If you don't have git: [Instructions](http://happygitwithr.com/install-git.html#install-git) 

### GitHub Issues

1. In this repository
2. Go to the Issues tab and open the Start Here! Issue (should be the only one)
3. React to some comments you like or dislike 
4. Make your own comment (optional)

### Make a Pull Request

1. Edit the [ggplot2-readme-problems.md](https://github.com/kellobri/rladies-dc-github-wkshp/blob/master/ggplot2-readme-problems.md) file directly in GitHub
2. Make a commit
3. Submit a PR (a request for your changes to be incorporated into my doc)

### Create a Git Repository

1. Create a new GH repo
2. Use RStudio to slurp it down locally
3. Do some work on it locally
4. Push that work back up to the master copy on GH

Workflow Reference: [Happy Git with R](http://happygitwithr.com/new-github-first.html)

### Practice Push and Pull Workflow

1. Edit your README again on GH
2. Commit your changes directly to master branch
3. Pull those remote changes to your local project
4. Always good to Pull before you start work

Discussion: Advanced Collaboration Related Topics
- Always pull before starting new work 
- Branching strategies: Sprint branches, Issue branches
- Git client GUIs for helping to navigate merge conflicts
- Try not to make "monster" commits

## Git/GitHub with R - Presentability

### Knit/Render Rmarkdown for GitHub

1. Add a default Rmd to your project
2. Knit to github_document
3. Commit and Push to GitHub
4. View the rendered files on GitHub

### GitHub Pages

1. Go to Settings
2. Scroll to GitHub Pages section
3. Select source: master branch
4. (optional) Select a theme
5. Visit your new site

## More References

### Git Panic! (Help Around Making Mistakes)

- [Oh Shit, Git!](http://ohshitgit.com/)

### Git Client Recommendations

- RStudio IDE is a very lightweight git client. If you're serious about git collaboration with other people, I recommend getting a Git Client. 
- Git Clients are great because they give you a GUI for untangling git messes
- Which client you should use is largely operating system dependent
- I don't have any personal recommendations - google: "best git clients" to get a sense of what's popular and try one out!


