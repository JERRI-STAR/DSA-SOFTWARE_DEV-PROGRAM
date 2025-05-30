This is for the Course I went or I am taking now.



A
A
A
A
A
B

Let me just a little something about Git and Github
DSA SOFTWARE DEVELOPMENT
To-Do Date: May 19 at 11:59pm
🚀 Pre-requisites for Using Git & GitHub

These apply across all systems:

    ✅ Basic Computer Use – Comfort with the terminal/command line will help, but we’ll keep it simple.

    🌐 Internet Access – Required to download Git and interact with GitHub.

    📧 GitHub Account – Sign up here 

    Links to an external site. (it’s free).

🪟 For Windows Users
1. Install Git

    Visit: https://git-scm.com 

    Links to an external site.

    Click Download for Windows.

    Run the installer:

        Keep default settings unless you know what you're doing.

        Choose your default editor (Notepad++ or VS Code is fine).

        Accept default line endings.

2. Verify Installation

Open Command Prompt and run:
git --version
3. Set Up Git (first-time only)
git config --global user.name "Your Name" git config --global user.email "your@email.com"
4. Install Git Bash (Optional but Recommended)

    Comes with Git installer.

    Git Bash is a terminal that works better for Git commands on Windows.

🍎 For macOS Users
1. Check if Git is Already Installed

Open Terminal and type:
git --version

If not installed, it will prompt to install Xcode Command Line Tools.
2. (Optional) Install Git via Homebrew

If you want to manage packages better:

    First install Homebrew 

    Links to an external site.:
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

    Then install Git:
    brew install git

3. Set Up Git
git config --global user.name "Your Name" git config --global user.email "your@email.com"
🐧 For Linux Users (Ubuntu/Debian-based)
1. Install Git

Open your terminal and run:
sudo apt update sudo apt install git

For Fedora:
sudo dnf install git
2. Verify Installation
git --version
3. Set Up Git
git config --global user.name "Your Name" git config --global user.email "your@email.com"
First Steps with GitHub
1. Create a GitHub Account

    Go to: https://github.com 

    Links to an external site.

    Sign up with your email and create a password.

2. Create a New Repository

    Click the "+" at the top right > New repository.

    Give it a name, optionally a description.

    Choose Public or Private.

    Check Initialize with a README (optional for beginners).

Connect Git to GitHub (Basic Workflow)
1. Clone a Repo to Your Local Machine
git clone https://github.com/your-username/your-repo.git cd your-repo
2. Make Changes and Push
# Edit files using your editor git add . git commit -m "Your message" git push origin main
🛠 Tools to Make It Easier

    🧰 VS Code – A great editor with Git built-in.

    🖼️ GitHub Desktop – GUI tool for Git (good for beginners):

        Download: https://desktop.github.com 

        Links to an external site.

📝 Summary Table
Task 	Windows 	macOS 	Linux
Install Git 	Use Git installer 	Xcode CLT or Homebrew 	apt / dnf
Check Git version 	git --version 	git --version 	git --version
Configure Git 	✅ 	✅ 	✅
Create GitHub Account 	✅ 	✅ 	✅
Clone Repo 	✅ 	✅ 	✅
Push Changes 	
To Do


