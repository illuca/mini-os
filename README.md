# How to download

```shell
git clone --recursive git@github.com:illuca/mini-os.git
```

# Overview

- Developed and extended a miniature operating system, implementing a vnode-based virtual file system for multi-process access
- Implemented system calls including open, read, write, lseek, close, dup2, execv, and waitpid to support process and file management
- Designed and integrated virtual memory management components such as page tables, TLB exception handling, and user page allocation
- Developed key memory management functions including as_create, as_prepare_load, and as_define_region to support efficient address space management