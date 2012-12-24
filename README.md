git-extra
=========

Some extra functionality for git.

Available commands:

*   git foreach

git foreach
-----------

Runs the command given as a parameter in each subdirectory of the current directory if it's a git repository (recursive).
Example:
    git foreach git status

You can supply the command which should be executed as a string (not a must).
Example:
    git foreach "git commit; git push"
