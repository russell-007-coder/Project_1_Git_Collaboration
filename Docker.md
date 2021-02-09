*What Is Docker?*

Docker is great at building and sharing disk images with others through the Docker Index
Docker is a manager for infrastructure (today's bindings are for Linux Containers, but future bindings including KVM, Hyper-V, Xen, etc.)
Docker is a great image distribution model for server templates built with Configuration * Managers (like Chef, Puppet, SaltStack, etc)
Docker uses btrfs (a copy-on-write filesystem) to keep track of filesystem diff's which can be committed and collaborated on with other users (like git)
Docker has a central repository of disk images (public and private) that allow you to easily run different operating systems (Ubuntu, Centos, Fedora, even Gentoo)

*How Docker Is Like Git*

Git's promise: Tiny footprint with lightning fast performance.

Docker has the same promise. Except instead of for tracking changes in code, you can track changes in systems. Git outclasses SCM tools like
Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows. 
Docker outclasses other tools with features like ultra-fast container startup times (microseconds, not minutes), convenient image building tools, and collaboration workflows.
