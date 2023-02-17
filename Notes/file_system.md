A file system is a system that allows:
- A mapping between names -> chunks of bytes

The mapping is implemented in many different ways, but all need some level of metadata, at least for the `name -> bytes` mapping.

Inode (index node) Numbers:
- Inode: `/usr/bin/ls -i`
- Stats: `stat file`

## File System Mounting

Associating a file system to a storage device in Linux is a process called `mounting`. The mount command is used to attach a file system to the current file system hierarchy (root). During a mount, you provide a file system type, a file system, and a mount point.

## References

- [File system Implementation](https://ceunican.github.io/aos/40.File_system_Implementation.pdf)
- [Introduction to File Systems](https://www.eecs.harvard.edu/~cs161/notes/intro-file-systems.pdf)
- [Anatomy of the Linux file system](https://developer.ibm.com/tutorials/l-linux-filesystem/)
- [What is a Superblock, Inode, Dentry and a File?](https://unix.stackexchange.com/questions/4402/what-is-a-superblock-inode-dentry-and-a-file)