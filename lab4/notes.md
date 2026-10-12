1)--global applies settings system-wide to your user account profile. Omitting it makes the setting local to your current repository or causes an error outside one.
2)The hidden .git directory appears because it starts with a dot. It holds Git’s internal database, object storage, branch references, and configuration files.
3)Git offers to track hundreds of files, including the .venv/ folder. Those files are third-party libraries and dependencies you did not write.
4)All thousands of untracked files inside .venv/ disappear from git status. Git actively ignores them based on your rules.
5).gitignore must be committed because it is a crucial project configuration file. Collaborators need the same rules to prevent pushing unwanted build files.
6)README.md moved from untracked files to the staging area ("Changes to be committed"). In the three-places model, it moved from the working directory into the index.
7)Git printed the root commit hash, summary message, and file change statistics. It confirmed how many files changed and total insertions/deletions.
8)They are called the short commit hash or short SHA-1. They act as unique cryptographic identifiers to quickly reference or checkout that exact historical snapshot.
9)The four steps are making edits, checking status (git status), staging changes (git add), and recording snapshots (git commit).
10)README.md is recognized globally by platforms like GitHub as the front-page description window. It automatically renders formatted documentation for project visitors.
11)gh auth login securely generates and stores an OAuth token on your machine. This authenticates your CLI tool so Git can push without password prompts.
12)The rendered contents of README.md show up on the front page. GitHub automatically looks for and displays this file as the default project overview.
13)Running git log --oneline shows pushing did not alter your local history timeline. Pushing simply copies your existing commits up to the remote server.
14)A private repository safely stores code on GitHub and shares it only with approved collaborators. A non-existent repository has no remote server record or online backup at all.
