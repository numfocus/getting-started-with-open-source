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


## Getting Started: Git Setup & First Pull Request

If you are new to open source, follow these simple steps to make your
first contribution.

### Step 1: Install Git
Download Git from:
https://git-scm.com/downloads

Check installation:
```bash
git --version

### Step 2: Configure Git
Set your name and email (required for commits):

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

### Step 3: Fork the Repository
Click the **Fork** button at the top-right of this repository.
This will create a copy of the repository under your GitHub account.

### Step 4: Clone the Repository
Clone your fork to your local machine:

```bash
git clone https://github.com/YOUR-USERNAME/getting-started-with-open-source.git
cd getting-started-with-open-source

### Step 5: Create a New Branch
Create and switch to a new branch:
git checkout -b my-first-contribution

### Step 6: Make Your Changes

Open README.md
Make your changes
Save the file

### Step 7: Commit Your Changes

Stage and commit your changes:

git add README.md
git commit -m "Improve README with Git setup and first PR steps"

### Step 8: Push Changes to GitHub
Push your branch to your fork:
git push origin my-first-contribution

### Step 9: Create a Pull Request

Go to your fork on GitHub
Click Compare & Pull Request
Add a short description
Submit the PR