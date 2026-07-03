# Question 5 Explanation

- I used `lsblk` to identify the available block devices and their partitions.
- I checked mounted filesystems with `mount` and reviewed capacity and inode usage with `df -h` and `df -i`.
- The storage assessment shows that the current environment has sufficient free space and low inode utilization, so it appears healthy for the current workload.
