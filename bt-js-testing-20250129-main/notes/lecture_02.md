2. Version Control Systems (git, GitHub)
Delete directory:

    rm demo
Exit from git log list just press 'q' key.

'HEAD' -> our current position (checkout) main -> local repository origin/main -> remote repository

    #  send updates from local to remote repo
    git push
    #  send updates from remote to local repo
    git pull
    # list all local branches
    git branch

    # create new branch
    git branch some_branch_name

    # create new branch and checkout
    git checkout -b some_branch_name
    # switch branch
    git checkout branch_name

    # switch (checkout) to any commit
    git checkout commit_id
    # Forcedly delete local branch
    git branch -D demo_branch_02

    # Delete remote branch
    git push -d origin <branch-name>
    git push -d origin demo_branch_01
    # merge branches
    git checkout branch_name_there_to_merge
    git merge branch_name_from
