The idea of the BranchingTest is to demonstrate a branching and merging strategy, with use of tags to delineate releases.

The primary branch is Develop. 'master' is renamed to 'Release' and is a protected branch, it may not be committed to except as a checked pull-request from Develop.

Notionally, the Release branch is the currently released version, so is merged /after/ a certain group of commits are released onto the production system, rather than before.
