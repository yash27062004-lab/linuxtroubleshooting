# Inode Exhaustion

**Issue:** Disk showed free space available, but new files could not be created.

**Checks:** Verified inode utilization, identified directories containing excessive numbers of files, and confirmed inode exhaustion.

**Result:** Located the source of inode consumption and restored inode availability.

**Key Learning:** A filesystem can run out of inodes even when disk space is still available.
