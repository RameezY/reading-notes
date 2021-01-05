# Git Notes

## What is GIT?
In a nutshell, GIT is a version control system, specifically a Distributed Version Control System (DVCS).  A DVCS allows you to have mirrored repositories.  That prevents or at least helps out with failure issues where the files might get corrupted or lost. You don't have a backup for it because it's all stored in one location, and no one is actively creating backups each time.

## Important Commands to Remember
To clone an existing Git repository to your local machine:
```
git clone https://github.com/your_repo
```

To determine the state of the files:
```
git status
```

To track and stage a single file:
```
git add filename
```

To track and stage all files:
```
git add *
```

Commit a single file with a message regarding changes made:
```
git commit -m "your message"
```

Commit all files:
```
git commit -a
```

Push your changes:
```
git push origin main
```

### Table of Contents
* [Reading Notes Home](README.md)
* [Growth Mindset](growth_mindset.md)
* [Markdown Reading](markdown.md)
* [Coders Computer](coders_computer.md)
* [Git Notes](git_notes.md)
* [What I Have Learned So Far](learned_so_far.md)
