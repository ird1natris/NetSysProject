# Net&Sys Assignment: Running Containers for Application Development

Group Name: __Dark Phoenix__ 

Team Mates:
1. __Irdina Batrisyia Binti Nor Azli__  __2117188__
2. __Sayyidah Nafisah Binti Johari__  __2118242__

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** __https://github.com/ird1natris/NetSysProject__.
2. How many files and folders are in this repository. ***(1 mark)*** __2 files and 1 folder__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __Ubuntu Linux__.
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __2 cores, 8 GB RAM, and 32 GB storage, up to 32 cores, 64 GB RAM, and 128 GB storage__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Committing and syncing work on source control ensures that all changes are saved and shared with team members, providing a backup, facilitating collaboration, and maintaining a history of changes for version control and auditing purposes__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)***
2. Run the command **cat /etc/passwd** . ***(1 mark)***
3. Run the command **df** . ***(1 mark)***
4. Run the command **du** . ***(1 mark)***
5. Run the command **ls** . ***(1 mark)***
6. Run the command **ls -asl** . ***(1 mark)***
7. Run the command **free -h** . ***(1 mark)***
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***
9. Run the command **top** and type **q** to quit. ***(1 mark)***
10. Run the command **uname -a**. ***(1 mark)***

```bash
@ird1natris ➜ /workspaces/NetSysProject (main) $ whoami
codespace
@ird1natris ➜ /workspaces/NetSysProject (main) $ pwd
/workspaces/NetSysProject
@ird1natris ➜ /workspaces/NetSysProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
@ird1natris ➜ /workspaces/NetSysProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 14451736  16701844  47% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24219136   6062656  80% /vscode
/dev/sda1       46127956       92  43752288   1% /tmp
/dev/loop3      32847680 14451736  16701844  47% /workspaces
@ird1natris ➜ /workspaces/NetSysProject (main) $ du
1972    ./images
8       ./.git/objects/60
8       ./.git/objects/b1
12      ./.git/objects/ff
12      ./.git/objects/02
8       ./.git/objects/c6
8       ./.git/objects/4b
8       ./.git/objects/41
12      ./.git/objects/d2
8       ./.git/objects/d8
8       ./.git/objects/e7
12      ./.git/objects/2e
8       ./.git/objects/4a
8       ./.git/objects/7b
20      ./.git/objects/fb
12      ./.git/objects/b0
8       ./.git/objects/fe
12      ./.git/objects/6e
8       ./.git/objects/fa
12      ./.git/objects/1c
8       ./.git/objects/f2
8       ./.git/objects/5b
1824    ./.git/objects/pack
12      ./.git/objects/70
12      ./.git/objects/64
12      ./.git/objects/44
8       ./.git/objects/74
8       ./.git/objects/0d
8       ./.git/objects/cb
8       ./.git/objects/46
8       ./.git/objects/8e
8       ./.git/objects/58
12      ./.git/objects/f0
12      ./.git/objects/14
8       ./.git/objects/3f
12      ./.git/objects/3d
12      ./.git/objects/af
8       ./.git/objects/54
12      ./.git/objects/f6
8       ./.git/objects/8c
8       ./.git/objects/83
8       ./.git/objects/91
8       ./.git/objects/b2
8       ./.git/objects/3a
12      ./.git/objects/73
8       ./.git/objects/93
8       ./.git/objects/97
16      ./.git/objects/b6
8       ./.git/objects/a6
8       ./.git/objects/71
12      ./.git/objects/c2
8       ./.git/objects/a3
8       ./.git/objects/04
8       ./.git/objects/eb
8       ./.git/objects/1a
8       ./.git/objects/fc
8       ./.git/objects/49
8       ./.git/objects/4f
8       ./.git/objects/c3
8       ./.git/objects/81
12      ./.git/objects/72
8       ./.git/objects/45
12      ./.git/objects/a1
8       ./.git/objects/0b
8       ./.git/objects/1b
8       ./.git/objects/f9
4       ./.git/objects/info
8       ./.git/objects/52
12      ./.git/objects/89
8       ./.git/objects/20
8       ./.git/objects/ee
8       ./.git/objects/86
8       ./.git/objects/fd
8       ./.git/objects/cd
12      ./.git/objects/62
12      ./.git/objects/b5
12      ./.git/objects/e5
12      ./.git/objects/17
12      ./.git/objects/7e
12      ./.git/objects/e9
8       ./.git/objects/47
8       ./.git/objects/24
8       ./.git/objects/96
16      ./.git/objects/b9
8       ./.git/objects/ab
2620    ./.git/objects
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/refs/tags
8       ./.git/refs/heads
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
8       ./.git/info
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
64      ./.git/hooks
4       ./.git/branches
2792    ./.git
4784    .
@ird1natris ➜ /workspaces/NetSysProject (main) $ ls
README.md  images
@ird1natris ➜ /workspaces/NetSysProject (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 May 20 14:58 .
 4 drwxr-xrwx+ 5 codespace root  4096 May 20 14:58 ..
 4 drwxrwxrwx+ 9 codespace root  4096 May 20 14:59 .git
16 -rw-rw-rw-  1 codespace root 12901 May 20 15:02 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 May 20 14:58 images
@ird1natris ➜ /workspaces/NetSysProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.4Gi       201Mi       1.0Mi       6.2Gi       6.0Gi
Swap:            0B          0B          0B
@ird1natris ➜ /workspaces/NetSysProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2445.427
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2645.294
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid
top - 15:13:15 up 18 min,  0 users,  load average: 0.20, 0.35, 0.49
Tasks:  17 total,   1 running,  16 sleeping,   0 stopped,   0 zombie
%Cpu(s):  4.1 us,  4.2 sy,  0.0 ni, 91.5 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    186.3 free,   1485.3 used,   6258.0 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6128.2 avail Mem
 
@ird1natris ➜ /workspaces/NetSysProject (main) $ 
    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                 
   2382 codespa+  20   0   21.1g 340164  43776 S   1.3   4.2   0:21.34 node                                                                                    
   3212 codespa+  20   0  726652  61544  38656 S   1.0   0.8   0:01.15 node                                                                                    
   2186 codespa+  20   0  970152 109124  42240 S   0.7   1.3   0:05.03 node                                                                                    
    776 root      20   0 1463360  86492  50304 S   0.3   1.1   0:00.17 dockerd
                                                                                 
@ird1natris ➜ /workspaces/NetSysProject (main) $ uname -a
Linux codespaces-ea28d8 6.5.0-1019-azure #20~22.04.1-Ubuntu SMP Wed Apr  3 03:28:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```

11. What is the available free memory in the system. ***(1 mark)*** __The available free memory is 201 MiB__.

12. What is the available disk space mounted on /workspace. ***(1 mark)*** __The available disk space mounted on /workspace is 16,701,844 1K-blocks (approximately 16 GB)__.

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __The version is 6.5.0-1019-azure and the hardware architecture is x86_64__.

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __ls command lists the names of files and directories in the current directory while ls -asl command lists files and directories with detailed information including file type and permissions, number of hard links, owner, group, size, last modification date and time with all entries including hidden files and size in blocks__.

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __The TLB size of the Virtual CPU is 6.2 GiB__.

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __The CPU speed of the Virtual CPU is 2445.427 MHz__.

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __The top running process that consumes the most CPU cycles is node with PID 2382__.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __Fill answer here__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Fill answer here__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __Fill answer here__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Fill answer here__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Fill answer here__.
2. What port is the apache web server running. ***(1 mark)***
3. What port is open for http protocol on the host machine? ***(1 mark)***

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __Fill answer here__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
4. What is the network address for the running container c1 and c2.
5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
