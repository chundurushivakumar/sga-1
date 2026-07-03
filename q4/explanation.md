# Question 4 Explanation

- I used file descriptor inspection through `/proc/$$/fd` to verify that Linux exposes open files through numeric descriptors.
- I redirected standard output and standard error to separate files and then combined them into one file to demonstrate how shell I/O works.
- I checked the shell limits with `ulimit -a` and observed that the environment allows a large number of open files, which is typical for a containerized development session.
