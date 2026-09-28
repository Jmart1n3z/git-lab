cards-a
## Card 1
Wrong commit message was written, I did commit --amend and wrote the correct text. 
I did not create a new commit, just edited the previous one.
## Card 2
The wrong file was added to the branch. I deleted the file so it no longer was in the branch.
The file was not in the branch anymore
## Card 3
The difference between each one was that using --soft kept the file staged, no flag made the file
unstaged, and --hard deleted the file 
## Card 4
A file that had an error was pushed to github. I used git revert HEAD to undo the last push and 
create a new one. This restored the file that was wrong.
## Card 5
I created the scratch.txt file and did a hard reset to 2 commits back, which caused the file to
delete, I used the reflog to find the entry at which the head had the file in it and moved to that 
one. After this, I could see the file again.
