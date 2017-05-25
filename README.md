# docker
Basic Instruction to setup docker on windows 7
install docker toolbox https://docs.docker.com/toolbox/overview/#next-steps
what docker toolbox will contains ?
1. you want to have Doker Engine(to create container and images) in order for Docker CLI Client running
2. you want to have Docker Machine(so that you can run Docker Engine from Windows terminal)
Problem: Because Docker Engine Deamon uses Linux-specific kernal feature you can't run Docker Engine natively on windows
Solution: you must use Docker Machine command to create and attach a small VM on your linux machine, This VM host Docker Engine for you on your windows system
3. Kitematic(Docker GUI)
4. Docker Quickstart Terminal
5. Oracle VM

My PC:Windows 7 x64
19.5 Gb remaining on C
at the time of writing this I'm installing Docker Toolbox version 17.04.0-ce
PC Location C:\Program Files\Docker Toolbox
Full installation Consist Of
Docker Client
Docker Machine
Docker Compose(Optional)
Virtual Box
Kitematic(Optional)
Git(Optional)


