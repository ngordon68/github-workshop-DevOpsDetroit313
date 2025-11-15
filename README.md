# github-workshop
Workshop example repo for getting familiar with GitHub!

Here are a few pointers for getting started with Git / GitHub:
- Create a GitHub account [here](https://github.com/signup) if you don't have one already
- Download a code editor (I recommend VS Code [here](https://code.visualstudio.com/)) if you don't have one already
- Clone this repository locally (`git clone git@github.com:MgenGlder/github-workshop.git` or `git clone https://github.com/MgenGlder/github-workshop.git`).
    - You may need to set up ssh keys.
       - [This guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) helps you create them.
       - [This guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) helps you add them to GitHub
- Create a new empty folder and navigate to it in the command line on your machine and open it in VS Code.
- Follow [these instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository) to create a new repository in GitHub
- Use `git init` to initialize a new repository on your machine from the command line
- Add a `README.md` file to your repository locally with the text `HELLO WORLD` and commit it locally.
   - Use `git add .` to add it to your staging area.
   - Use `git commit -m "Update readme"` to commit it locally.
   - Use `git push` to push it to GitHub.
- Push the change to your repository (on the `main` branch).


 ### Fast Movers
 - Attempt to create a pull request.
   - Checkout out a new branch with `git checkout -b update-readme`.
   - Make a small change to your `README.md` (add the current date, `11/15/25` to the top).
   - Use `git add .` to add it to your staging area.
   - Use `git commit -m "Update readme"` to commit it locally.
   - Use `git push` to push the new commit and the branch to GitHub.
   - Navigate to your GitHub repository and use the UI to create a pull request.
   - [🥇Extra Credit] Find another person's pull request, and make a comment or suggestion on it.
- Attempt to create an issue.
   - Go to the `Issues` tab in your new GitHub repository.
   - Add a new issue with the title `Add more information about the GitHub workshop` and give it any description.
- Fork a repository.
   - Go to https://github.com/dearborn-coding-club/website-base-backend and fork it using the icon in the top right.
   - [🥇Extra Credit] Clone your forked repository, make a small change the readme, create a pull request, and point it at the original repository. Feel free to ask for help here!!
