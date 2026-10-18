![DISC logo](./assets/DISC.png)

# Overcoming barriers to entry in Open Source projects

This repository contains documents and resources on getting started with Open
Source projects.

This resource was created as part of the [NumFOCUS DISC Unconference](https://pydata.org/nyc2017/diversity-inclusion/disc-unconference-2017/).  📃 Read about its creation on the [NumFOCUS blog](https://numfocus.org/blog/getting-started-open-source-notes-numfocus-disc-unconference).

### [Why contribute to Open Source?](./what_is_open_source_and_why_contribute.md)
Wondering why you contribute to Open Source?  Here are a few good reasons it can benefit both you and the world!

### [Compilation of Open Source Resources](./compilation_of_open_source_resources.md)
This file includes a collection of external resources (links) that elaborate on how to contribute to Open Source projects effectively as a newbie.

### [How to organize an Open Source sprint](./how_to_organize_an_open_source_sprint.md)
An Open Source sprint is a short event where groups of people get together to work on a single Open Source project with help from its maintainers.  We provide detailed instructions and resources for organizing an Open Source sprint at your company, club or Meetup Group. 


### [Meet the Contributors](./open_source_stories.md)
About the contributors to this repo and their Open Source experience.

## Getting Started with Git and GitHub

New to Open Source contributions? Git and GitHub help you track code changes and collaborate with other developers.

### 1. Install Git

Download Git from the [official Git website](https://git-scm.com/downloads) and follow the installation instructions for your operating system.

After installation, open your terminal or command prompt and run:

git --version

If Git is installed correctly, this command displays the installed version.

### 2. Fork and clone a repository

Fork: Create your own copy of the original repository by clicking the Fork button on its GitHub page.

Clone: Download your fork to your computer so you can work on it locally.

Open your fork on GitHub, copy its URL, and run:

git clone https://github.com/YOUR-USERNAME/REPOSITORY.git
cd REPOSITORY

Replace YOUR-USERNAME and REPOSITORY with your GitHub username and the repository name.

### 3. Create a branch and make your changes

Create a separate branch for your contribution:

git checkout -b <branchname>

Make your changes to the relevant files, then stage and commit them:

git add .
git commit -m "Add my first contribution"

### 4. Push your branch to GitHub

Upload your branch to your fork:

git push -u origin <branchname>

### 5. Open a Pull Request

Visit your fork on GitHub. GitHub may display a prompt to create a Pull Request for your recently pushed branch.

Create the Pull Request against the original repository's appropriate base branch. Describe what you changed and why, and link the related issue if applicable.

The maintainers will review your contribution and may request changes before merging it.

Tip: Before contributing to any project, read its CONTRIBUTING.md file and follow its specific setup, testing, and Pull Request guidelines.

For more details, see the [GitHub guide to contributing to a project](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project).