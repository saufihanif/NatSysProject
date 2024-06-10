# Net&Sys Assignment: Running Containers for Application Development

Group Name: NetNovators 

Team Mates:
1. HANIF SAU'FI BIN SAIFUL AZMI 2322451    

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** 
```
github.com/saufihanif/NatSysProject
```

3. How many files and folders are in this repository. ***(1 mark)*** 
```
1 Folders and 2 Files
```


***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** 
```
Ubuntu
```

2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
```
(2 core 8GB Ram) and (4 core 16GB Ram)
```

3. Why must we commit and sync our current work on source control? ***(1 mark)*** 
```
Source control allows you to track changes to codebase
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```
/workspaces/NatSysProject
```

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```
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
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin__.
3. Run the command **df** . ***(1 mark)*** __Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10381540  20772040  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24271896   6009896  81% /vscode
/dev/sda1       46127956      156  43752224   1% /tmp
/dev/loop3      32847680 10381540  20772040  34% /workspaces
```

4. Run the command **du** . ***(1 mark)*** 
```
1972    ./images
8       ./.git/info
4       ./.git/branches
4       ./.git/lfs/tmp
8       ./.git/lfs
8       ./.git/refs/heads
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
4       ./.git/refs/tags
32      ./.git/refs
8       ./.git/logs/refs/heads
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
28      ./.git/logs/refs
36      ./.git/logs
8       ./.git/objects/c3
8       ./.git/objects/0d
4       ./.git/objects/info
8       ./.git/objects/fe
8       ./.git/objects/83
8       ./.git/objects/5e
8       ./.git/objects/86
8       ./.git/objects/8e
8       ./.git/objects/b2
8       ./.git/objects/24
12      ./.git/objects/b5
12      ./.git/objects/1c
12      ./.git/objects/70
12      ./.git/objects/14
8       ./.git/objects/58
8       ./.git/objects/a3
8       ./.git/objects/47
8       ./.git/objects/93
12      ./.git/objects/73
8       ./.git/objects/cd
12      ./.git/objects/a1
8       ./.git/objects/e7
8       ./.git/objects/74
12      ./.git/objects/3d
8       ./.git/objects/f6
8       ./.git/objects/bd
8       ./.git/objects/cb
12      ./.git/objects/6e
8       ./.git/objects/0b
8       ./.git/objects/ef
8       ./.git/objects/04
8       ./.git/objects/91
8       ./.git/objects/4a
8       ./.git/objects/90
12      ./.git/objects/d2
8       ./.git/objects/e9
8       ./.git/objects/c2
12      ./.git/objects/72
8       ./.git/objects/b9
16      ./.git/objects/62
8       ./.git/objects/fa
12      ./.git/objects/af
8       ./.git/objects/b6
8       ./.git/objects/11
12      ./.git/objects/44
8       ./.git/objects/52
8       ./.git/objects/31
16      ./.git/objects/1b
12      ./.git/objects/64
12      ./.git/objects/17
8       ./.git/objects/a6
8       ./.git/objects/7b
8       ./.git/objects/eb
8       ./.git/objects/3f
16      ./.git/objects/fb
8       ./.git/objects/81
8       ./.git/objects/60
8       ./.git/objects/ab
8       ./.git/objects/3c
8       ./.git/objects/71
8       ./.git/objects/4f
8       ./.git/objects/f3
8       ./.git/objects/5b
12      ./.git/objects/2e
12      ./.git/objects/41
1824    ./.git/objects/pack
8       ./.git/objects/49
8       ./.git/objects/c6
8       ./.git/objects/4b
16      ./.git/objects/20
8       ./.git/objects/d8
8       ./.git/objects/3a
8       ./.git/objects/f9
8       ./.git/objects/96
8       ./.git/objects/f2
8       ./.git/objects/fd
8       ./.git/objects/fc
12      ./.git/objects/ff
12      ./.git/objects/e5
2552    ./.git/objects
68      ./.git/hooks
2744    ./.git
4732    .
```

5. Run the command **ls** . ***(1 mark)***
```
README.md  images
```

6. Run the command **ls -asl** . ***(1 mark)*** 
```
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 Jun 10 18:17 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jun 10 18:17 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jun 10 18:31 .git
16 -rw-rw-rw-  1 codespace root 13617 Jun 10 18:32 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jun 10 18:17 images
```

7. Run the command **free -h** . ***(1 mark)*** 
```
total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.7Gi       818Mi       1.0Mi       5.3Gi       5.8Gi
Swap:            0B          0B          0B
```

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3244.369
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
cpu MHz         : 3243.500
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
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```

9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
```
processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.500
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
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vms
top - 18:34:11 up  2:47,  0 users,  load average: 0.05, 0.20, 0.21
Tasks:  28 total,   1 running,  27 sleeping,   0 stopped,   0 zombie
%Cpu(s):  3.7 us,  3.7 sy,  0.0 ni, 92.5 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    808.5 free,   1719.1 used,   5402.0 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   5894.3 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                            
   7779 codespa+  20   0   21.5g 350260  49920 S   0.7   4.3   0:26.37 node                                                                                               
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.22 docker-init                                                                                        
      8 codespa+  20   0    7236   1792   1792 S   0.0   0.0   0:00.01 sleep                                                                                              
     65 root      20   0   12196   3480   2560 S   0.0   0.0   0:00.00 sshd
```

10. Run the command **uname -a**. ***(1 mark)*** 
```
Linux codespaces-5897c8 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```

11. What is the available free memory in the system. ***(1 mark)*** 
```
779Mi
```

12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
```
Filesystem      Size  Used Avail Use% Mounted on
overlay          32G   10G   20G  34% /
tmpfs            64M     0   64M   0% /dev
shm              64M  8.0K   64M   1% /dev/shm
/dev/root        29G   24G  5.8G  81% /vscode
/dev/sda1        44G  160K   42G   1% /tmp
/dev/loop3       32G   10G   20G  34% /workspaces
```

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
```
Linux codespaces-5897c8 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
```
-a: This option shows all files, including hidden files (those whose names start with a dot .).
-s: This option displays the size of each file in blocks.
-l: This option produces a detailed listing, showing information such as permissions, number of links, owner, group, size, and modification date for each file
```

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
```
modern processors to reduce the time taken to access memory locations
```

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
```
__2 cpu and 3 cpu__.
```

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
```
7779 codespa+  20   0   21.5g 340104  49920 S   0.7   4.2   0:31.42 node.
```

## Running your own container instance.

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)***
```
Containers are designed to be lightweight. Meaning that they are typically isolated environments that do not retain data between runs.
```

2. Can we run two, or three instances of debian linux? . ***(1 mark)***
```
Yes, docker allowes user to create multiple instance
```

## Running your own container with persistent storage

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)***
```
-rw-r--r--
```

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```
Yes, you can change the permissions of the files
```

## You are on your own, create your own static webpage

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)***
```
-rw-rw-rw- 1 codespace codespace 337 Jun 10 20:52 index.html
```

2. What port is the apache web server running. ***(1 mark)***
```
80
```

3. What port is open for http protocol on the host machine? ***(1 mark)***
```
8080
```

## Create SUB Networks


***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)***
```
The --name switch in Docker is used to assign a specific name to a container
```

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
```
NETWORK ID     NAME      DRIVER    SCOPE
7f55f57ce607   bluenet   bridge    local
872972994d95   bridge    bridge    local
98af44506347   host      host      local
a2bddf0b81aa   none      null      local
deb52be46267   rednet    bridge    local
6d45423693f3   subnet1   bridge    local
baabcc656f43   subnet2   bridge    local
```

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
```
Bluenet: 172.18.0.1
Rednet: 172.19.0.1
```

4. What is the network address for the running container c1 and c2.
```
Bluenet: 172.18.0.2
Rednet: 172.19.0.2
```

5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***
```
PING 172.21.0.2 (172.21.0.2) 56(84) bytes of data.
64 bytes from 172.21.0.2: icmp_seq=1 ttl=64 time=0.056 ms
64 bytes from 172.21.0.2: icmp_seq=2 ttl=64 time=0.060 ms

```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

```
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.151 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.097 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.105 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.092 ms
```
