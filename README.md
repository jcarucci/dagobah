# Dagobah
## Git lessons from master Yoda

### Summary
The most important thing to understand about git is that it is a distributed system. Every cloned repo has a full copy and all are equally valid. cvs, subversion, etc don't work this way. They have one master server.

### Most Important Commands
- Learn how to use git from the command line first. GUIs can make life easier, but they can't do everything and you end up not really understanding what is going on if you just click buttons.
- To get help on any command use git help
    - `git help clone`
    - `git help branch`
    - `git help` <-- This will list the commands
- Make a full copy of a repo: `git clone`
    - This repo: `git clone https://github.com/jcarucci/dagobah.git`
    - Get source code for git: `git clone https://github.com/git/git.git`
    - Get Python: `git clone https://github.com/python/cpython.git`
- See changes: `git diff`
- Stage files and or changes: `git add`
- Record changes in git: `git commit`
- Show all commits: `git log`
- Show or create branch: `git branch`
- Get branch: `git checkout`
- Show or create remote connections: `git remote -v`
- Push changes to remote: `git push`
- Pull changes from remote: `git pull`

### My Recommended Workflow
1. Create the repo on github first. Even though you can create it on your PC first, it's just way easier to create an empty repo on github to start. Create a .gitignore and README file.
2. git clone this new repo
3. Always work on branches, even if you're the only one doing the work
4. git push branch to github (you can do this as many times as you like)
5. When done, open a pull request on github to merge the branch into master (main)
6. Use releases/tags on github to mark versions you're happy with, makes it easier to go back to that point in the future.

### Further Reading
- Free book [Pro Git](https://git-scm.com/book/en/v2)
- Online [reference](https://git-scm.com/docs), same information you can get from git help