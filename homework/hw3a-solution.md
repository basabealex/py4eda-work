# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.
### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections
## Part 2: Portfolio Repository Creation
I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
### Understanding Git Workflow
The three-stage workflow:
1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`
## Part 3: GitHub Publishing
Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub
### The Remote Connection
My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
### Details
Complete this section with details from your setup:
- Repository URL: https://github.com/basabealex/py4eda-work
- Output of `git remote -v`: 

origin  https://github.com/basabealex/py4eda-work.git (fetch)
origin  https://github.com/basabealex/py4eda-work.git (push)

-he output of `git log --oneline`:

e4d4c3b (HEAD -> master, origin/master) Add hw3a solution document
e7eec93 Initial commit: Add README and .gitignore

## Questions ##
### Reflections
QUESTION 1
a) Before this assignment I tried to organize everything from the files on my PC trying to organize everything using folders. If i wanted to save an older version of a file i had to create a copy of the document.
With Git it is much simpler as you can save all the versions you want of the project with the commit tool making it much easier, efficient and clean.
The 3 main advantages in my opinion are:
--> You can control the version of the project and keep a track of the changes in history. You can go back to any previous version of the project.
--> Very good for collaboration with other people. You can see what changes in the project each person made.
--> From what i've read, the work is always safe as it is stored in the cloud

b) When working in my last internship i had to make a project using excel VBA (macros). Using this tool would have been really helpful to keep a track of the changes I made because I would forget what things i changed two weeks ago for example.

QUESTION 2
a) It is important to keep these separate because they are different things, one is my project and the other one is a copy of Dan's. If we would try to put everything into one repository it would become a mess and things would interact between each other since some file names may be the same.
b) I would keep each project/assignment separate from each other in different repositories to have an organized structure and know where everything is without issues.

QUESTION 3
a) The second message is more usefull as it tells us exactly what we need to do. We might want to find this commit in the future if we make a change and it makes the project stop working as expected.
b) I would commit before making any important change to the code. I don't see a reason not to commit often. A significant change to the project structure may be a goo "unit of work" for a single commit.

