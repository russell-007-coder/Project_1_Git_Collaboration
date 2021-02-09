*What Is Docker?*

Docker is great at building and sharing disk images with others through the Docker Index
Docker is a manager for infrastructure (today's bindings are for Linux Containers, but future bindings including KVM, Hyper-V, Xen, etc.)
Docker is a great image distribution model for server templates built with Configuration * Managers (like Chef, Puppet, SaltStack, etc)
Docker uses btrfs (a copy-on-write filesystem) to keep track of filesystem diff's which can be committed and collaborated on with other users (like git)
Docker has a central repository of disk images (public and private) that allow you to easily run different operating systems (Ubuntu, Centos, Fedora, even Gentoo)

*When To Use Docker?*

Docker is a basic tool, like git or java, that you should start incorporating into your daily development and ops practices.

Use Docker as version control system for your entire app's operating system
Use Docker when you want to distribute/collaborate on your app's operating system with a team
Use Docker to run your code on your laptop in the same environment as you have on your server (try the building tool)
Use Docker whenever your app needs to go through multiple phases of development (dev/test/qa/prod, try Drone or Shippable, both do Docker CI/CD)
Use Docker with your Chef Cookbooks and Puppet Manifests (remember, Docker doesn't do configuration management)

*How Docker Is Like Git*

Git's promise: Tiny footprint with lightning fast performance.

Docker has the same promise. Except instead of for tracking changes in code, you can track changes in systems. Git outclasses SCM tools like
Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows. 
Docker outclasses other tools with features like ultra-fast container startup times (microseconds, not minutes), convenient image building tools, and collaboration workflows.
