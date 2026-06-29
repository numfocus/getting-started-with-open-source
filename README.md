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

***

## 🚀 Getting Started & Your First Contribution

Welcome! If you are joining us through events like Hacktoberfest, GSoC, or NumFOCUS, this guide will help you quickly set up your local workspace environment and successfully submit your very first open-source Pull Request (PR) to this repository.

### 1. Install Git
Before contributing, you need Git source control installed on your system:
* **Official Download**: Visit the [Official Git Downloads Page](https://git-scm.com) and download the appropriate package installer for Windows, macOS, or Linux.
* **Ubuntu / WSL2 Users**: Open your Linux command terminal pane and run the following command directly:
  ```bash
  sudo apt update && sudo apt install git -y
  ```

### 2. Fork and Clone the Repository
Instead of making changes directly to this main project layout, you will safely develop updates on your own cloud copy (called a "fork"):
1. Scroll to the top-right corner of this GitHub screen and click the **Fork** button.
2. Once the fork repository layout is generated under your personal GitHub profile account, copy its project URL path.
3. Open your terminal screen and execute a clone command to download the text files to your computer machine (remember to replace `YOUR_USERNAME` with your actual personal GitHub username structure):
   ```bash
   git clone https://github.com
   cd open-source-barriers
   ```

### 3. Make Your First Pull Request (PR)
Follow these standard industry development steps to safely capture your workspace adjustments:

* **Step 3.1: Create a safe workspace branch**
  Never save structural edits directly onto your local `main` branch. Spin up a separate, isolated testing sandbox workspace branch layout:
  ```bash
  git checkout -b my-first-contribution
  ```

* **Step 3.2: Save your file edits**
  Open the repository documentation folder pages inside your preferred code studio editor workspace (such as VS Code), adjust the text files, and hit save.

* **Step 3.3: Stage and commit your changes**
  Run these targeted index tracking flags to declare exactly which file updates you want to snapshot log into Git history:
  ```bash
  git add .
  git commit -m "docs: add clear Git setup and beginner contribution steps to README"
  ```

* **Step 3.4: Push code up to GitHub**
  Upload your sandbox tracking branch line directly up to your personal upstream GitHub storage account fork:
  ```bash
  git push origin my-first-contribution
  ```

* **Step 3.5: Submit the PR**
  Go back to your personal fork page on the GitHub website. You will see a yellow banner appear at the top. Click **"Compare & pull request"**, fill out a short summary of what you did, and click the green **"Create pull request"** button!