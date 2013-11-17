## CIS 191 Project 3
-----------------

This is a demo site that is a simplified version of the CIS 191 website. It is
used as a testbed/training ground for Git usage and merge conflict resolution.

1.  The post-receive hook waits until the changes are finished being pushed to the server. It then changes the git work tree to ~/www, checks out the deploy branch to copy the files over, echos a "server starting" message, and finally changes directories to ~/www and runs the server in the background.
2.  The python server serves the current directory (in this case, ~/www) when it is run, so the public can see index.html, homework.html, etc.
3.  A bare repository is a git repository that does not contain a working directory
