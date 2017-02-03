The idea of the BranchingTest is to demonstrate a branching and merging strategy, with use of tags to delineate releases.

The primary branch is Develop. 'master' is renamed to 'Release' and is a protected branch, it may not be committed to except as a checked pull-request from Develop.

Notionally, the Release branch is the currently released version, so is merged /after/ a certain group of commits are released onto the production system, rather than before.

Once released, the Release branch is merged to from Develop; which is also tagged with the released version. The tag commit on Develop is the result of merging one or more feature branches into Develop, and then branching from develop into ReleasePrep\_/n/ where N is the version to be released, an update number, normally.
