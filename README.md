# FireAntOS
Operating System for SuperComputing.

The goal of FireAntOS is to provide an "operating system" that has all the essential components of supercomputing and resource management/sharing. 

The Setup will require multiple nodes (servers) connected over a high speed network; each running the same version of FireAntOS. Then a head node will be established to initiate tasks, so the network of computer systems can function as a single processing unit. To establish the connection, I will be implementing secure, preconfigured backdoors that access the file systems and run/kill threads. 

Currently, i plan on laying this "operating system" over a linux distribution (Ubuntu) to leach off the essential set up of an OS(boot loader, running processes, network connection). The main software will initially focus primarily on connecting the resources, and the rest can be programmed later. 

main tasks:

Shared File Systems: Basically, a version of nautilus that focuses on accessing the file systems of each node. It should easily shutil files to each system (possible drag and drop function), check shared files for consistency, list files etc. 

Terminal: basically normal terminal functions, but shows data for all nodes.

Threading: the ability to run x threads on each system. It should be able to start threads, kill threads (without losing data), maintain threads etc.

Compiler: make programmed code readable for the super computer. the scripts will be read differently, so a package should be installed that converts the scripts into a readable language/ set up monitors, logs etc.

This is the starting guide for now, and i'm a rather new programmer with no experience. So, if i make major mistakes, please guide the project in the right direction. i will be posting code later with more details. Also, I'm aware that people write software for these tasks, but this is a project that i'm passionate about.  This is a personal project i'm working on for mathematical calculations, but hopefully it can become a bigger project!

