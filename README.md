## Welcome to Thirty Minutes to Merge

A project based learning activity for people who are getting started with branching with Git.

You can play the game at: https://githubschool.github.io/thirty-minutes-to-merge/

>> _*SUPPORTED BROWSERS*: Chrome, Firefox, Safari, Opera and IE9+_

This fun open source game was cloned from: https://github.com/jakesgordon/javascript-tetris

Slide Deck: [Branching Strategies.pdf](https://github.com/githubschool/thirty-minutes-to-merge/files/6069357/Branching.Strategies.pdf)


## Initial Repo Setup (Student)
Enable GitHub Pages in Repository Settings:
1. Click the "Settings" tab in the repository navigation menu
1. Scroll down to the heading that reads "GitHub Pages"
1. Click the button that says "None" to select which branch you would like to serve your GitHub page from.  For this demo, choose "main".
1. Click "Save" button to save this setting.
1. Once saved, you will be provded with a URL where your GitHub Page is being hosted.

Enable GitHub Actions:
1. Click the "Actions" tab in the repository navigation menu
1. Click the large green button that reads "I understand my workflows, go ahead and enable them"

## GitHub Flow
[GitHub Flow Graphic](https://guides.github.com/introduction/flow/)
![github_flow image](https://github.com/githubschool/thirty-minutes-to-merge/blob/main/github_flow.png)

Choose a branching strategy that works for you, here are some things to consider about GitHub Flow:
- Simple and easy to manage
- Fast and light weight - "deploy early, deploy often"
- Works well with CI/CD strategies
- Good for continuous release 
- Doesn't support multiple versions

### Hands on activity
:octocat: Oh no! The link in our README file isn't correct. Let's use the GitHub Flow to correct our README file.
- [ ] TODO - Fix the URL in the README.md file.
1. Create a branch
1. Edit the README.md file and fix the URL. Save and commit your changes.
1. Open a Pull Request - add some information about the chages you are proposing. Let the collaboration begin!
1. Merge your approved changes into the main branch.
1. :tada: Celebrate! You just completed the GitHub Flow. :tada:

---

## Git Flow
![git_flow image](https://github.com/githubschool/thirty-minutes-to-merge/blob/main/gitflow_1.png)

Choose a branching strategy that works for you, here are some things to consider about Git Flow:
- Works well in slow development/deployment flow
- Better suited for longer development cycles and a more structured development process
- Works well if you need to maintain multiple versions in production
- Good for planned releases
- Slower, more methodical process
- "Heavy-weight" - more overhead


### Hands on activity
1. Create a feature branch from the main branch named `feature-changespeed`
1. On line 78 of the `index.html` file, alter the `start` and `min` values.
1. Create a feature branch from the main branch named `feature-changecolor`
1. On lines 116 through 122 of the `index.html` file, alter the `color`values to any color you like.
1. Create a pull request from each feature branch into the `develop` branch.
1. Review and approve each Pull Request and merge the new feature into the `develop` branch
1. Time to go to production! Now open a pull request from the develop branch into the main branch.
1. Time for final review and approval, then promote the develop branch to production - merge develop into production.

While following along, if you don't want to create the branches and make modifications to the files in the repository you can use the following branches when we discuss a Git Flow workflow:

- `ex-changespeed`
- `ex-changecolor`
