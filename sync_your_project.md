# Prerequisites
- [Install](https://github.com/cli/cli#installation) GitHub CLI interface
- In the command line, authenticate to GitHub. <br> `gh auth login`

# Optional: Register a github account
- [Sign up](https://github.com/signup/) a new github account
- Inform [Bolun](https://github.com/BolunHan) your username/email and wait for an organization invitation

# Optional: init git repo
- In the command line, navigate to the root directory of your project.
- Initialize the local directory as a Git repository. <br> `git init -b main`

# Create a new repo on github
- Create a repository for your project on GitHub, <br> `gh repo create sanjincapital/<your_project-name>`
- Follow the interactive prompts.
- Pull changes from the new repository that you created. <br> `git pull --set-upstream origin main`
- Stage, commit, and push all of the files in your project. <br> `git add . && git commit -m "initial commit" && git push`
