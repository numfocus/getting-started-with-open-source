![DISC logo](./assets/DISC.png)

# Overcoming barriers to entry in Open Source projects

This repository contains documents and resources on getting started with Open
Source projects.

This resource was created as part of the [NumFOCUS DISC Unconference](https://pydata.org/nyc2017/diversity-inclusion/disc-unconference-2017/).  📃 Read about its creation on the [NumFOCUS blog](https://numfocus.org/blog/getting-started-open-source-notes-numfocus-disc-unconference).

### Installing Git

Git is essential for contributing to Open Source projects. Follow these steps to get started:

1. **Download Git** from the official website: [https://git-scm.com/install/](https://git-scm.com/install/)
2. **Run the installer** and follow the setup instructions for your operating system (Windows, macOS, or Linux)
3. **Verify the installation** by opening a terminal and running:
   ```
   git --version
   ```
4. **Configure your identity** (required for commits):
   ```
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

### How to Fork and Clone a Repository

**Forking** creates your own copy of a repository on GitHub, and **cloning** downloads it to your local machine.

#### Step 1: Fork the Repository
1. Go to the GitHub repository you want to contribute to
2. Click the **Fork** button in the top-right corner of the page
3. Select your account as the destination for the fork
4. Wait for GitHub to create your copy of the repository

#### Step 2: Clone Your Fork
1. On your forked repository page, click the green **Code** button
2. Copy the URL (HTTPS or SSH)
3. Open a terminal and run:
   ```
   git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
   ```
4. Navigate into the cloned directory:
   ```
   cd REPOSITORY-NAME
   ```

#### Step 3: Set Up the Upstream Remote
Link your local clone to the original repository to stay updated:
```
git remote add upstream https://github.com/ORIGINAL-OWNER/REPOSITORY-NAME.git
```

Verify your remotes:
```
git remote -v
```
You should see `origin` (your fork) and `upstream` (the original repo).

#### Step 4: Keep Your Fork Updated
Before making changes, sync with the original repository:
```
git fetch upstream
git checkout main
git merge upstream/main
```

Now you're ready to create a branch, make changes, and submit a pull request!

### Making Your First Pull Request

Here's a complete workflow example for contributing to an Open Source project:

#### Step 1: Create a New Branch
Always create a new branch for your changes (never work directly on `main`):
```
git checkout -b fix-typo-in-readme
```
Use a descriptive branch name that reflects your changes.

#### Step 2: Make Your Changes
Edit the files you want to change using your preferred code editor. For example, fix a typo, add documentation, or implement a feature.

#### Step 3: Stage Your Changes
Add the files you've modified to the staging area:
```
git add filename.md
```
Or stage all changes:
```
git add .
```

#### Step 4: Commit Your Changes
Write a clear, descriptive commit message:
```
git commit -m "Fix typo in README.md"
```

#### Step 5: Push to Your Fork
Push your branch to your GitHub fork:
```
git push origin fix-typo-in-readme
```

#### Step 6: Create the Pull Request
1. Go to your fork on GitHub
2. You'll see a prompt to **Compare & pull request** – click it
3. Ensure the base repository is the original project and the base branch is `main`
4. Write a clear title and description explaining your changes
5. Reference any related issues (e.g., "Fixes #42")
6. Click **Create pull request**

#### Step 7: Respond to Feedback
- Maintainers may request changes – this is normal!
- Make additional commits to your branch to address feedback
- Push the new commits; they'll automatically appear in the PR
- Be patient and polite in discussions

#### Example Workflow Summary
```
# 1. Sync with upstream
git fetch upstream
git checkout main
git merge upstream/main

# 2. Create a feature branch
git checkout -b add-installation-guide

# 3. Make changes, then stage and commit
git add README.md
git commit -m "Add installation guide to README"

# 4. Push and create PR
git push origin add-installation-guide
# Then go to GitHub and open a Pull Request
```

🎉 **Congratulations!** You've made your first Open Source contribution!

### [Why contribute to Open Source?](./what_is_open_source_and_why_contribute.md)
Wondering why you contribute to Open Source?  Here are a few good reasons it can benefit both you and the world!

### [Compilation of Open Source Resources](./compilation_of_open_source_resources.md)
This file includes a collection of external resources (links) that elaborate on how to contribute to Open Source projects effectively as a newbie.

### [How to organize an Open Source sprint](./how_to_organize_an_open_source_sprint.md)
An Open Source sprint is a short event where groups of people get together to work on a single Open Source project with help from its maintainers.  We provide detailed instructions and resources for organizing an Open Source sprint at your company, club or Meetup Group. 


### [Meet the Contributors](./open_source_stories.md)
About the contributors to this repo and their Open Source experience.
