[A successful git branching model](http://nvie.com/posts/a-successful-git-branching-model/)

"From the classic CVS/Subversion world I came from, merging/branching has always been considered a bit scary (“beware of merge conflicts, they bite you!”) and something you only do every once in a while."

"[...]with Git, these actions are extremely cheap and simple, and they are considered one of the core parts of your daily workflow...Version control tools are supposed to assist in branching/merging more than anything else."

- 'essentially no more than a set of procedures'

**Intro:**  

- Central "truth" repo
- Display image
- Developers can all have their own remotes, or share branches on the
  origin

**Main branches**

- **Master** reflects *production-ready* code
- Every push to master condsidered a new release
- **Develop** reflects on-going development, for the next release, also
  called the *Integration Branch*
- **Develop** is where nightly builds come from
- When **Develop** is stable nough for a release, we make our way down
  to **Master**

**Supporting Branches**

- **Feature, Release, Hotfix**
- Special only in a policy sense; still just git branches
