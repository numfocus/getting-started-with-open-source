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



### [Prerequisities](./knowing%20the%20steps.md)
Prerequisites for Starting with Open Source are
Essential things to know before contributing.


### What is Git?
Git is a distributed version control system used to track changes in files, especially source code, enabling efficient collaboration among multiple developers.



To knonw more explore https://git-scm.com/


### How to Install Git
Choose your operating system:

For Windows
Visit the official Git website: https://git-scm.com/download/win

Download the Git installer for Windows.

Run the installer and follow the setup wizard with default recommended settings.

After installation, open Command Prompt or Git Bash and verify by running:


git --version
### For macOS
The easiest method is using Homebrew. Open Terminal and run:


brew install git
Alternatively, download the Git installer from https://git-scm.com and install it.

Verify installation by running:


git --version

Configure Git (All Operating Systems)
After installing Git, set your name and email to identify your commits:


git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
### After Installing Git Next Steps :
Congrats! You've completed 50% of your journey to your first open source contribution.

To continue:

Create a GitHub profile if you don't have one: https://github.com/join

Choose a repository you want to contribute to and open it on GitHub.

Click the Fork button on the top-right to create your own copy of the repo.

Click the green Code button, copy the HTTPS URL.

Open your terminal or command prompt and clone your fork using:


git clone <paste-the-copied-url>
Navigate inside the cloned repository folder to start making changes.

### Example Workflow for Your First Pull Request
Fork the Repository
Go to the repository on GitHub and click "Fork" to create a copy under your account.

Clone Your Fork Locally


git clone https://github.com/your-username/repository-name.git
cd repository-name
Create a New Branch
Keep your work organized by branching off from the main branch:


git checkout -b feature-branch-name
Make Your Changes and Commit
Edit files locally and then:


git add .
git commit -m "Clear, concise message describing what you changed"
Push Your Branch to GitHub


git push origin feature-branch-name
Create a Pull Request on GitHub
Visit your forked repo on GitHub; you’ll see a prompt to open a pull request for your pushed branch.
Click Compare & pull request, add a description explaining your changes, and submit.

Respond to Feedback
If maintainers request changes, make updates locally, commit again, and push. Your PR updates automatically.

Celebrate Your Contribution!
Once reviewed and approved, your changes will be merged into the main project. You’ve made a positive impact!

T






 


### Example Workflow for First Pull Request
Fork the Repository
On GitHub, navigate to the repository you want to contribute to and click the "Fork" button to create your own copy of the repo.

Clone Your Fork Locally
In your terminal, run:
git clone https://github.com/your-username/repository-name.git
cd repository-name


Create a branch for your changes to keep your work separate from the main branch:
git checkout -b feature-branch-name


Edit files locally. After changes:
git add .
git commit -m "A clear message describing your changes"


git push origin feature-branch-name


On GitHub, go to your forked repository. A prompt usually appears to create a pull request for your pushed branch. Click "Compare & pull request". Add a description explaining your changes and submit the PR
