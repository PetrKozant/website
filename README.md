How to use GitHub from VS CODE

git status
git add -A
git commit -m "Add comment to the commit"
git push


git status
Shows your current branch, which files are modified, staged, untracked, or deleted, and whether you’re ahead/behind the remote.
Makes no changes; it’s just a report.


git add -A
Stages all changes for the next commit: new files, modifications, deletions, and renames.
Tip: git add . won’t stage deletions; -A does.


git commit -m "Add comment to the commit"
Creates a new commit from the staged changes with the given message.
Only staged changes are included; nothing is uploaded yet.


git push
Sends your local commits to the remote repository (usually origin) on the current branch.
If it says no upstream, run: git push -u origin $(git branch --show-current) once, then use git push next time.



Create directory  "Images"
mkdir -p Images