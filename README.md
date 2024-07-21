[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15344584&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:
Step-by-Step Guide to Setting Up Your Development Environment
1. Download and Install Windows 11
Visit Microsoft's Windows 11 download page and follow the instructions to download and install Windows 11 on your machine.

2. Install Visual Studio Code
Go to the Visual Studio Code download page.
Download the installer for Windows and run it.
Follow the installation instructions to complete the setup of Visual Studio Code.

3. Set Up Version Control System (Git)
Install Git:
Download Git for Windows from git-scm.com.
Run the installer and follow the prompts to install Git on your machine.
Configure Git:
Open Git Bash or the command prompt and set up your username and email:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Optionally, configure Git with additional settings like editor preference:
bash
Copy code
git config --global core.editor "code --wait"
Create a GitHub Account:

Go to GitHub and sign up for a new account if you don't have one.
Initialize a Git Repository and Make Your First Commit:
Create a new directory for your project.
Initialize a Git repository:
bash
Copy code
git init
Create some files, stage them, commit them:
bash
Copy code
echo "# My Project" >> README.md
git add README.md
git commit -m "Initial commit"

4. Install Python and Necessary Tools
Download Python from python.org.
During installation, ensure you select the option to add Python to PATH.
Verify installation by opening a command prompt and typing:
- bash
- Copy code
python --version
Install pip (Python package manager) if not installed automatically:
- bash
- Copy code
python -m ensurepip

5. Install MySQL Database
Download MySQL from MySQL Community Downloads.
Run the installer and follow the prompts to install MySQL Server and MySQL Workbench.

6. Optional: Set Up Development Environments and Virtualization
Consider using Docker or virtual machines (e.g., VirtualBox) to manage project dependencies and ensure consistent environments.

7. Explore Extensions and Plugins for Visual Studio Code
Open Visual Studio Code and explore extensions from the Extensions view (Ctrl+Shift+X).
Install extensions relevant to your programming languages and project needs (e.g., Python, GitLens, Docker).

8. Document Your Setup
Create a detailed document outlining each step of your setup process.
Include screenshots where necessary to illustrate configurations or installations.
Document any customizations, configurations, or troubleshooting steps encountered.

9. Create GitHub Repository
Create a new repository on GitHub for your project.
- Push your local Git repository to GitHub:
bash

git remote add origin https://github.com/yourusername/your-repository.git
git branch -M main
git push -u origin main

10. Submission
Compile your setup document and ensure it includes all necessary details and screenshots.
Share the GitHub repository link along with your setup document through the designated platform or via email. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
