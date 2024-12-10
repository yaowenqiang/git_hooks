# Git Hooks

Extensibility points that are triggered when certain Git actions occur

## Types of Hooks

+ Pre-

Called before the Git command executes, Can abort the Git command

+ Post-

Called after the Git command executes, Do not affect the Git command

+ Misc.

Called while the Git command executes, can abort the git command

## Types of Git Hooks(commit Workflow)


prepare-commit-msg
commit-msg


Characteristics of Git Hooks

+ Can be written in any language
+ Command line arguments, input, output, error streams, and environment variables
+ Git checks exit code to determine success of failure
+ Neutral to IDE
+ Run in the same Git working directory

Clinet-side vs. Server-side Hooks

Client-side

+ Can be easily disabled by removing them or using Git switched
+ Can be easily forgotten
+ Mainly for developer's own productivity and defensive style

Server-side

+ Can be easily disabled by removing them
+ Cannot be bypassed by client commands
+ Main to enforce server-side policy on Git repos

/usr/share/git-core/templates/hooks/

https://github.com/learntobuild-dev/git-hook








