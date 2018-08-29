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

1.  Once site is configured, make sure that your online repo is up-to-date using Github Desktop or via command line:

    ```
    git push origin master
    ```

2. 