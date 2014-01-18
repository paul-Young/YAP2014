YAP2014
=======

Important Dates

1. Feb 6 2PM: registration deadline
2. Feb 6 8PM: contest begins
3. Feb 10 8PM: electronic solution due
4. Feb 19: mailed solution must be received

Data Organization
-------

### paper: 
This is the main working folder

1. paper/section will contain separte sections of the paper
2. paper/figure will contain all the figures we want to include
3. paper/ref will contain all the references we wish to cite

### code: 
This folder will contain any and all code we wish to write for the project

Working Through GIT
-------
DO NOT SYNC unless you're absolutely certain that all changes are correct

1. clone newest repository from https://github.com/paul-Young/YAP2014
2. ASK everyone which file they're working on, if two people edit the same file in different ways, life can get complicated.
3. If you screw up **locally**:
        a.run "git revert HEAD^1..HEAD" to go back 1 commit, "git revert HEAD^2..HEAD" to go back 2 etc.
        b.if you're confident the last commit was not needed run "git reset --hard HEAD"
4. If you SYNCED your screw-up.... Let Paul handle it