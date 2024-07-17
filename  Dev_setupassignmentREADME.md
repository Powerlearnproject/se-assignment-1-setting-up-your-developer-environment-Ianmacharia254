Setting Up Your Development Environment
Table of Contents
Operating System: Install Windows 11
Text Editor or IDE: Install Visual Studio Code
Version Control System: Install Git and GitHub Setup
Programming Languages: Install Python
Package Managers: Install pip for Python
Database: Install MySQL
Development Environments and Virtualization (Optional)
Explore Extensions and Plugins for Visual Studio Code

1. Operating System: Install Windows 11
Steps:
Visit the Windows 11 Download Page.
Click on "Download now" and run the installer.
Follow the on-screen instructions to install Windows 11 on your machine.
Once installed, proceed to set up your user account and complete the initial setup.



Screenshot of Windows 11 Download Page

2. Text Editor or IDE: Install Visual Studio Code
Steps:
Go to the Visual Studio Code Download Page.
Download the installer suitable for your operating system.
Run the installer once downloaded.
Follow the installation prompts (e.g., select destination folder, create desktop icon).
Complete the installation process.



3. Version Control System: Install Git and GitHub Setup
Steps:
Download Git from the Git Official Website.
Run the downloaded installer.
Follow the installation prompts (e.g., select components, choose editor, adjust PATH environment).
Open a command prompt and verify Git installation:
bash

git --version
Configure Git with your username and email:
bash

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub account at GitHub if you haven't already.
Initialize a Git repository for your project:
bash

git init
Create a new repository on GitHub and follow the instructions to add a remote origin and push your first commit.


Screenshot of Git Installation

4. Programming Languages: Install Python
Steps:
Download Python from the Python Official Website.
Run the installer.
During installation, make sure to check the option to add Python to PATH.
Click "Install Now" and wait for the installation to complete.
Verify Python installation by opening a command prompt and typing:
bash

python --version


Screenshot of Python Installation

5. Package Managers: Install pip for Python
Steps:
pip usually comes installed with Python. Verify its version by typing:
bash

pip --version
Upgrade pip to the latest version using:
bash

python -m pip install --upgrade pip


Screenshot of upgrading pip

6. Database: Install MySQL
Steps:
Download MySQL from the MySQL Official Website.
Run the downloaded installer.
Choose "Custom" setup type to customize your installation.
Select MySQL Server and other components as per your requirements.
Complete the installation process and set a root password when prompted.
Screenshots:

Screenshot of MySQL Installation

7. Development Environments and Virtualization (Optional)
Steps (for Docker):
Download Docker from Docker Official Website.
Run the installer and follow the installation wizard.
Once installed, Docker should start automatically. You can verify by checking the system tray.
Screenshots:

Screenshot of Docker Installation

8. Explore Extensions and Plugins for Visual Studio Code
Steps:
Open Visual Studio Code.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar (or using Ctrl+Shift+X).
Search and install extensions relevant to your programming languages and workflow (e.g., Python, GitLens).

Screenshot of Visual Studio Code Extensions

9. Customizations and Troubleshooting
Customizations:
Configured Visual Studio Code with preferred themes and extensions (e.g., Python, GitLens).
Set up Git repositories for multiple projects and configured .gitignore files.
Troubleshooting Encountered:
Git Configuration Issues: Ensured correct global configuration of Git settings to avoid authentication errors during GitHub operations.
MySQL Connection Errors: Troubleshot MySQL connectivity issues by verifying firewall settings and MySQL service status.









