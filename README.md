# course-stub

Hugo-based themeset for creating course websites with Reveal.js slideshows 

Demo:  https://mjvo.github.io/course-stub


## Instructions

[draft]

### Fork Own Repo for New Courses

1. Create a new (empty) repository https://github.com/new, using the default settings. Recommend using course # (and possibly year-semester for repo name, e.g. `vmsXXX-fXXXX`).

2.  Make a local copy of this new repo using "Open in Desktop" button on github.com or by using the command line:

    ```
    git clone https://github.com/<username>/vmsXXX-fXXXX.git
    ```

3.  Add "course-stub" repo as an Upstream Remote:

    ```
    cd vmsXXX-fXXXX
    git remote add upstream https://github.com/<username>/course-stub.git
    ```
4.  Update local copy of new repo with files from "course-stub" remote:

    ```
    git pull upstream master
    ```

5.  Push newly populated repo back up to Github:

    ```
    git push origin master
    ```
    


### Publishing site to gh-pages   
https://gohugo.io/hosting-and-deployment/hosting-on-github/

1.  Once site is configured, make sure that your online repo is up-to-date using Github Desktop or via command line.

2. Double-check that you don't have any uncommitted changes.  Commit them and push local repo to remote.

    The next step (specifically the `git reset --hard`) will DELETE any changes.  BE CAREFUL!

3.  cd into your local repo and run the following commands:

    ```
    git checkout --orphan gh-pages
    git reset --hard
    git commit --allow-empty -m "Initializing gh-pages branch"
    git push origin gh-pages
    git checkout master
    ```


