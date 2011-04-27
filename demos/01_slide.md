!SLIDE 
# Demos #

!SLIDE commandline incremental
# git-flow feature start #
    $ git-flow feature start demos
    Switched to a new branch 'feature/demos'

    Summary of actions:
    - A new branch 'feature/demos' was created based on 'develop'
    - You are now on branch 'feature/demos'

    Now, start committing on your feature. When done, use:

         git flow feature finish demos

!SLIDE commandline incremental
# git-flow feature finish #
    $ git-flow feature finish demos
    Switched to branch 'develop'
    Merge made by recursive.
     demos/01_slide.md |   30 ++++++++++++++++++++++++++----
     1 files changed, 26 insertions(+), 4 deletions(-)
    Deleted branch feature/demos (was 78cf742).

    Summary of actions:
    - The feature branch 'feature/demos' was merged into 'develop'
    - Feature branch 'feature/demos' has been removed
    - You are now on branch 'develop'

!SLIDE center
# I'm the Map! #
![I'm the Map!](git_branching_model.png)
