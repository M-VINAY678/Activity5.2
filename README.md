Git stash:

First created directory and initialized with the git<br>
created two files and one file is staged and another is not tracked.<br>
Now used stash (git stash push) then only the tracked files are stashed<br>
Then used (git stash push -u) , then all the files tracked and untracked files are stored temporarily.<br>
Then used git stack pop for bringing all files to directory.<br>

Git clean 

In the above we have one staged and one unstaged file.<br>
So when we used git clean , then it removed unstaged file.<br>

Interactive Staging

For this I used git add -i to enter into interactive mode.<br>
It given 8 options.<br>
Then I choosed option 4 i.e is add untracked.<br>
Then it displays untracked files along with number.<br>
Now I selected all files by using numbers<br>
After enter, it staged all files that I have entered <br>

Undoing changes:

used git revert for undoing commits<br>
git revert hashcommit<br>

Show:

used git show and git show --oneline to see the present commit history having diff, commit message<br>

Reflog:

It shows all commit with hashcode <br>
so we can use this hashcode when we unexpectedly delete some commit 
