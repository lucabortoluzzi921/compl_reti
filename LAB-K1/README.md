# LAB-K1. Docker hands-on

Aim of this lab activity is to become familiar with the basic commands of `docker`, required in the following labs.

NOTE WELL: If you work on the PCs in Dijkstra's room, it is advisable to always use the same PC for the whole course, as your files will be stored on that machine (only).

ON DIJKSTRA PCs:

To access the Ubuntu virtual machine (VM) in the Dykstra lab using a PC:

*Item 1 At the GUI login screen, enter username and password as follows:

Username: complreti
Password: reti2026PWD

* Item 2 Once logged in, the Ubuntu VM will automatically start and display in full-screen console mode.

* Item 3 Run Docker.

**Shutdown Steps:**

Shut down properly by running the command poweroff in the terminal (or via the GUI shutdown menu if available).

Do not use the host PC's power button, Ctrl+Alt+Del, or close the window—this can corrupt the VM.

Wait for the VM to power off fully, then log out of the host PC GUI.

The full-screen view maximizes the console; use Ctrl+Alt or lab-specific keys to switch if needed (test during first session).

Please report any login or VM startup issues to the lab supervisor as soon as possible.


ON YOUR DEVICE:
0. Download and install Docker (if you are on your own device).

1. Open a terminal and type `docker run hello-world` to check that `docker` works properly

2. Open the tutorial on https://docker-curriculum.com/ with the Chrome browser 
> [!TIP]
> Follow carefully the steps below and do not skip any detail, since they will become very useful in the following labs.
3. Read the section **INTRODUCTION** and answer to the following questions:
   - Q1: What is a container and how is it different from a Virtual Machine (VM)? In which terms containers are "better" than VMs?
   - Q2: What is the meaning of _isolation_ for  VMs and containers?

> [!WARNING]
> Skip the section **GETTING STARTED**

4. Follow step-by-step the **HELLO WORLD** section and answer to the following questions:
   - Q3: What is the meaning of `docker pull` command?
   - Q4: What is the meaning of `docker images` command and how is related to the `docker pull`?
   - Q5: What is the meaning of `docker run` command and how is it related to `docker images`? 
   - Q6: What is the difference between an _image_ and a _container_?
   - Q7: What is the meaning of `docker ps` command and how is it related to `docker run`?
   - Q8: What is the difference between `docker ps` and `docker ps -a`?
   - Q9: What is the meaning of `docker rm` command and how is it related to `docker ps`?   
   - Q10: What is the meaning of `docker container prune`?
   - Q11: What is the meaning of `docker rmi` and how is it related to `docker container prune`?







