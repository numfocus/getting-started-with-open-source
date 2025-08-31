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

### **1. Installing Git**

First, you'll need **Git**, the version control system we use to manage the project.

* **Windows:** [Download Git for Windows](https://git-scm.com/download/win).
* **macOS:** Install with Homebrew by running `brew install git`.
* **Linux (Debian/Ubuntu):** Run `sudo apt-get install git`.

You can verify your installation by running `git --version` in your terminal.

---

### **2. Forking and Cloning the Repository**

To work on the project, you need your own copy of it.

1.  **Fork the Repository:** On our GitHub page, click the **"Fork"** button in the top-right corner.
2.  **Clone Your Fork:** In your terminal, run `git clone https://github.com/YOUR-USERNAME/repository-name.git`.
3.  **Add the Upstream Remote:** Navigate into your project folder and run `git remote add upstream https://github.com/ORIGINAL-OWNER/repository-name.git`. This helps you keep your fork in sync with the main project.

---

### **3. Your First Pull Request**

Ready to make your first change? Follow this simple workflow.

1.  **Create a New Branch:** Run `git checkout -b new-feature-branch` to create a new branch for your changes.
2.  **Make and Commit Changes:** After your edits, stage your files with `git add .` and then commit them with a descriptive message like `git commit -m "docs: adds a guide for new contributors"`.
3.  **Push to Your Fork:** Push your new branch to your forked repository on GitHub with `git push origin new-feature-branch`.
4.  **Open a Pull Request:** Go to your fork on GitHub. You should see a banner at the top prompting you to **"Compare & pull request"**. Click on it to submit your changes for review.
