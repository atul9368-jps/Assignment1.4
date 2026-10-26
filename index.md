Step 1: Install Git and Verify
If you haven't already, download and install Git from git-scm.com.

Open your terminal (Command Prompt, PowerShell, or Terminal on macOS/Linux) and run the following command to make sure it's installed correctly:

Bash
git --version
Step 2: Open the Terminal in Your Project Folder
Create a new folder on your computer for your project (for example, name it my-git-project).

Open your terminal and navigate to that folder using the cd command:

Bash
cd path/to/your/my-git-project
(Tip: On many systems, you can also right-click inside your project folder and select Open in Terminal or Open Git Bash here).

Step 3: Run git init
Initialize an empty Git repository in your project folder by running:

Bash
git init
Step 4: Configure Your Git Username and Email
Set up your identity so your commits are tied to your name and email. Run these two commands (replace with your own details):

Bash
git config user.name "Your Full Name"
git config user.email "your.email@example.com"
Step 5, 6 & 7: Create an HTML File and Make 3 Meaningful Commits
To meet the requirement of 3 meaningful commits, you will create an HTML file and make three separate changes, committing each change step-by-step.

Commit 1: Create the basic HTML file
Create a file named index.html in your project folder and add a basic HTML skeleton:

HTML
<!DOCTYPE html>
<html>
<head>
    <title>My First Project</title>
</head>
<body>
</body>
</html>
Check the status of your files:

Bash
git status
Stage and commit the file:

Bash
git add index.html
git commit -m "Initial commit: Add base index.html file"
Commit 2: Add a heading
Open index.html and add a heading inside the <body> tags:

HTML
<body>
    <h1>Welcome to My Website</h1>
</body>
</html>
Stage and commit the change:

Bash
git add index.html
git commit -m "Add main heading to index.html"
Commit 3: Add a paragraph
Open index.html again and add a paragraph below the heading:

HTML
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first project tracked using Git.</p>
</body>
</html>
Stage and commit the final change:

Bash
git add index.html
git commit -m "Add introductory paragraph to index.html"
Checking Your Work for Submission
To prepare your screenshots for the assignment submission:

Repository Folder Screenshot: Take a screenshot of your project folder showing the index.html file (and make sure hidden files are visible if you want to show the hidden .git folder).

Commit History Screenshot: Run the following command in your terminal to display your history nicely:

Bash
git log --oneline
Take a screenshot of the terminal showing all 3 commits you just created.