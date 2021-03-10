# Notes I took during the workshop
- In issues, we can open posts about problems and then invite collaborators to fix them. For example, Pier opened an issue and tagged Tobias in it #3. He tagged it with bug. When Tobias fixed it, he typed "fixes #3" in his commit and the issue was automatically closed on the website.
- Always do "git pull" before you commit or push any changes.
- How to work on the same file: branching. "git branch", "git checkout issue-5", "git status", "git commit -m "Addressing #5"", "git push", "git push --set-upstream origin issue-5"
- Pull request: we did everything by commenting and copy-pasting links in the web interface.
- We merged issue-5 and main on web interface. It also gives you the commands you would use in terminal.
- Then, we deleted the extra branch. Clean up after yourself. 
- Locally: "git branch", "git checkout main"
On the second day, we will practice this all.

- go to the website, start a new issue, tag yourself, say what you need to do, add links
- git branch, git branch issue-7, git branch, git checkout issue-7
- git status, git add, git commit -m (say here fixes issue-7), git push (it will give you the precise git push command)
- move to client, fix issues and merge stuff there
- make a pull request
- merge pull request
- on terminal pull again, then switch back to main (checkout main), then delete branch 7

## Questions:
- I don't see Pier's repository in my GitHub accoount.
- Can all collaborators merge branches?
- When you "checkout" a new fork, can you give it any name?
