# Linux + Git Cheat Sheet (15 commands)

> Format: **Command** — what it does — example

## Linux Commands
1. **pwd** — print current directory — `pwd` (useful before running cd)
2. **ls** — list files — `ls -la`  (shows hidden files with -a)
3. **cd** — change directory — `cd ..`  (use cd .. to go up one directory)
4. **mkdir** — create a folder — `mkdir projects`  (use -p to create parent folders)
5. **touch** — create empty file — `touch notes.txt`  (also updates file timestamp)
6. **cp** — copy files — `cp a.txt b.txt`  (use -r to copy folders)
7. **mv** — move/rename — `mv old.txt new.txt`  (also used to rename files)
8. **rm** — delete — `rm file.txt`  (use -r for directories, be careful)
9. **cat** — view file content — `cat readme.md`  (useful for quick file viewing)
10. **grep** — search text — `grep "main" file.txt`  (use -i to ignore case)

## Git Commands
11. **git status** — show changes — `git status`  (check files before commit)
12. **git add** — stage changes — `git add .`  (stages changes for commit)
13. **git commit** — save snapshot — `git commit -m "message"`  (always write a clear message)
14. **git branch** — list/create branches — `git branch`  (use -d to delete a branch)
15. **git merge** — merge branch into current — `git merge branch-name`  (merges another branch into current)

