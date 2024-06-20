[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15300391&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Step 1: Download Windows 11
1.Go to the Windows 11 download page.
2.Click on "Download Now" under the "Windows 11 Installation Assistant" section.
3.Follow the instructions provided by the Windows 11 Installation Assistant to upgrade your OS.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Step 2: Download and Install Visual Studio Code
1.Go to the Visual Studio Code download page.
2.Select the appropriate installer for Windows.
3.Run the installer and follow the setup wizard to complete the installation.
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
Step 3: Install Git
1.Go to the Git download page.
2.Download the installer for Windows.
3.Run the installer and follow the setup wizard to complete the installation.
Step 4: Configure Git
1.Open Git Bash.
2.Set your username: git config --global user.name "Your Name"
3.Set your email: git config --global user.email "youremail@example.com"
Step 5: Create a GitHub Account
1.Go to the GitHub sign-up page.
2.Follow the instructions to create a new account.
Step 6: Initialize a Git Repository
1.Create a new directory for your project: mkdir my-project && cd my-project
2.Initialize a new Git repository: git init
3.Create a README file: echo "# My Project" > README.md
4.Add the README file to the repository: git add README.md
5.Make your first commit: git commit -m "Initial commit"
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Step 7: Install Python
1.Go to the Python download page.
2.Download the latest installer for Windows.
3.Run the installer and ensure you check "Add Python to PATH" before installing.
4.Verify the installation: Open Command Prompt and run python --version.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Step 8: Install pip
1.Pip is included with Python from version 3.4 and above. It should be installed automatically with Python.
2.Verify the installation: Open Command Prompt and run pip --version.
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step 9: Download and Install MySQL
1.Go to the MySQL download page.
3.Download the MySQL Installer.
4.Run the installer and follow the setup wizard to complete the installation.
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Step 10: Install Docker 
1.Go to the Docker Desktop download page.
2.Download and install Docker Desktop for Windows.
3.Follow the setup wizard to complete the installation.
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Step 11: Install Visual Studio Code Extensions
1.Open Visual Studio Code.
2.Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
3.Search for and install the following extensions:
-Python
-GitLens
-Docker
-Prettier - Code formatter
-python debugger
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
Challenges and Strategies:
Windows 11 Installation Issues:
Challenge: Compatibility issues and system requirements not met.
Strategy: Used the PC Health Check tool provided by Microsoft to ensure compatibility and upgraded hardware where necessary.
Git Configuration Problems:
Challenge: Incorrect user information set up.
Strategy: Double-checked and corrected the user configuration using git config --global --edit.
Python Path Not Found:
Challenge: Python executable not found in the system PATH.
Strategy: Reinstalled Python ensuring "Add Python to PATH" was checked and manually added Python to the system environment variables.
MySQL Installation Errors:
Challenge: Installation errors due to conflicting software.
Strategy: Uninstalled conflicting software and used the MySQL Installer Community for a guided setup.
Docker Performance Issues:
Challenge: Docker Desktop performance was slow on Windows.
Strategy: Allocated more resources (CPU and memory) to Docker Desktop through its settings and ensured that virtualization was enabled in the BIOS.
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
