# Question 3 Explanation

- I created a regular file, a hard link, and a symbolic link to compare how Linux handles each type of link.
- I used `ls -li` and `stat` to confirm that the hard link shares the same inode as the original file, while the symbolic link has its own inode.
- I removed the original file and observed that the hard link still worked because it points to the same inode, whereas the symbolic link became broken because it points to a path that no longer exists.
