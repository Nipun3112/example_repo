md = markdown

"git status" - initially shows this file as unstaged

"git add <file name.md>" - adding this file moved from unstaged to staged

check status - "git status" - will show file added

now to move in unstage/untracked status - "git restore --staged <file name>"

now if there is chnaged in file then status will be updated then do add it again 

commit it again  - "git commit -m info.md"

Then puch to main branch -  "git push origin main"

Now if there is update in file from local and need to check the difference before commit then - "git diff info.md"