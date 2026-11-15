Git & GitHub Workshop Exercise

Follow these steps to make your first Pull Request!

# 0. Prerequisites

a. Install Git from git-scm.com/downloads.
b. Authenticate your terminal with GitHub (see prerequisites.md for Windows PowerShell instructions).
c. Tell Git who you are by running these two commands once in your terminal:
```
git config --global user.name "Your Name"
git config --global user.email "your-github-email@example.com"
```

# 1. Fork & Clone

Click the Fork button at the top-right of this page to create your own copy of the repository.
On your fork's page, click the green Code button, make sure HTTPS is selected, and copy the URL.
Open your terminal (CMD, PowerShell, or your code editor's terminal) and run
(replace YOUR-USERNAME with your actual GitHub username):
```
git clone https://github.com/YOUR-USERNAME/training.git
cd training
```

# 2. Create a Branch & Make Your Edit

Create and switch to a new branch:
```
git checkout -b my-feature
```

Open the attendees.md file and replace the placeholder line with your name and a short message. Save the file.

# 3. Commit & Push

Stage your change:
```
git add .
```

Commit your change with a descriptive message:

git commit -m "Add my name to attendees"
