# docker
Basic Instruction to setup docker on windows 7
install docker toolbox https://docs.docker.com/toolbox/overview/#next-steps
what docker toolbox will contains ?
1. you want to have Doker Engine(to create container and images) you need Docker CLI Client which Docker Toolbox Provides to you
2. you want to have Docker Machine(so that you can run Docker Engine from Windows terminal)
Problem: Because Docker Engine Deamon uses Linux-specific kernal feature you can't run Docker Engine natively on windows
Solution: you must use Docker Machine command to create and attach a small VM on your linux machine, This VM host Docker Engine for you on your windows system
3. Kitematic(Docker GUI)
4. Docker Quickstart Terminal
5. Oracle VM
