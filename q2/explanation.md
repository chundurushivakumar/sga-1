# Question 2 Explanation

- I created the secure workspace directories and project files so the lab had a realistic structure to protect.
- I changed the permissions after creation to make the directories accessible only to the owner and group, while the files were restricted to read access for the owner and group.
- I verified the ownership with `stat` and confirmed it remained `codespace:codespace`.
- I checked the `umask` value and observed `0022`, which is the standard setting that limits write access for group and others.
