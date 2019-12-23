The `pre-receive` script is a drop-in GIT pre-receive hook which runs `ansible-review` on each
commit in a (fast-forwardable) push, rejecting changes if they can't be verified to be correct.
