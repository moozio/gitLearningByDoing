# Update Forked Repo

1. `clone` forked repo to local device.

    ```bash
    git clone
    ```

2. add the original repo as a remote source to local repo.

    ```bash
    git remote add ALIAS git://github.com/***/***.git
    # or
    git remote add --track BRANCH_NAME ALIAS git://gothub.com/***/***.git
    ```

3. `fetch` all branches of the ALIAS source to present local repo

    ```bash
    git fetch ALIAS
    ```

4. `checkout` to `master` branch

    ```bash
    git checkout master
    ```

5. `merge` ALIAS to local repo

    ```bash
    git merge ALIAS/master
    ```

6. `push` new repo to remote forked repo

    ```bash
    git push origin master
    ```
