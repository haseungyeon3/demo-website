# Demo-Website

Repo for students to practice creating a pull request after forking a repo

Scenario:  Hooray! We're building our course website (https://haseungyeon3.github.io/demo-website/)! Please remember not to share any confidential information on the site.
As part of the project, I'll be collecting your favorite animals and displaying the distribution on the website. To participate, simply add your favorite animal to the index.html file and submit a pull request to me.

1. First, make a fork of the GitHub repo.

    a. Visit URL: [https://github.com/haseungyeon3/demo-website/](https://github.com/haseungyeon3/demo-website/)

    b. In the top right corner of the screen, click on the down arrow next to "Fork" and select "Create a new fork." This creates an independent copy of the GitHub repo, which is then saved as a repository under your GitHub account.

    *Note that if you are already listed as a collaborator on the repo, or it is your own repo, you can skip this step in practice.
2. Launch the terminal from your local drive.

3. Clone the forked GitHub repository from your GitHub account (`git clone https://github.com/your-username/demo-website.git`), replacing `your-username` with your actual GitHub username.

5. Navigate to the folder in a terminal window (if you haven't already) and run:

    a. `git checkout main` (make sure you are on the main branch)
    
    b. `git branch dev` (create the new branch-if 'dev' already exists, use different name)
    
    c. `git checkout dev` (checkout the new branch)

6. Edit `index.html` on your local machine in the directory by adding your favorite pet to the file and save it.
   --> under section with id ="projects", enclosed within an 'li' tag 

8. In the terminal window run:

    a. `git status` (should show that `index.html` has been modified but is not in the staging area)
    
    b. `git add .` (Should add `index.html` to the staging area; run `git status` if you want to confirm this)
    
    c. `git commit -m "comment here"`
    
    d. `git push --set-upstream origin dev` (set up and use a classic security token if needed to be able to do this)
    --> 'git remote -v' to list all remote branches in terminal 


6. Create a pull request on GitHub to merge your changes from your forked repository into the original repository:

    a. Navigate to your forked repository on GitHub by going to the URL: [https://github.com/your-username/demo-website](https://github.com/your-username/demo-website), replacing `your-username` with your actual GitHub username.

    b. At the top of your repository, locate and click on the "Pull Requests" tab.

    c. Click the green "New Pull Request" button.

    d. On the "Compare changes" page, ensure that the "base repository" is set to `haseungyeon3/demo-website` and the "base" branch is set to `main`.

    e. In the "head repository" drop-down, select your forked repository.

    f. Choose the `dev` branch (or the branch where you made your changes) as the "compare" branch.

    g. Review the changes and ensure that they are as you intended.

    h. If everything looks good, click the "Create Pull Request" button.

    i. Give your pull request a meaningful title and description. Describe the changes you made and why they are necessary.

    j. Once you're satisfied with your description, click the "Create Pull Request" button again.

    k. Your pull request will now be visible in the original repository's pull requests. Other collaborators can review your changes, provide feedback, and discuss any potential modifications.

    l. If there are no conflicts and your changes are approved, the repository owner or collaborators can merge your pull request by clicking the "Merge Pull Request" button.

    m. Congratulations, your changes are now part of the original repository!
