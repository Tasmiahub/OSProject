# OSProject Running Containers for Application Development

Group Name: __Pookie__. 

Section: __Section 06__. 

Team Mates:
1. __Tasmia Rahman__ and __2112488__
2. __Salmaan Mohammad Hanif Bhat__ and __2114727__
3. __Shopno Md Tanvir Ahmmed__ and __2219061__
4. __Musanna Sarder Abdullah__ and __2220429__

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** __[https://github.com/Tasmiahub/OSProject](https://github.com/Tasmiahub/OSProject)__.
2. How many files and folders are in this repository. ***(1 mark)*** __1 folder 7 files__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __Ubuntu Linux__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __From 2 cores, 8 GB RAM, and 32 GB storage, up to 32 cores, 64 GB RAM, and 128 GB storage__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Our work will be lost since it is not saved into the main repository__.

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
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject
```
2. Run the command **cat /etc/passwd** . ***(1 mark)***
```bash
Tasmiahub ➜ /workspaces/OSProject (main) $ cat/etc/passwd
bash: cat/etc/passwd: No such file or directory
```
3. Run the command **df** . ***(1 mark)*** 
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ df 
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10380984  20772600  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24350708   5931084  81% /vscode
/dev/sda1       46127956      100  43752280   1% /tmp
/dev/loop3      32847680 10380984  20772600  34% /workspaces
```
4. Run the command **du** . ***(1 mark)***

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ du
8       ./webpage
8       ./.git/refs/heads
4       ./.git/refs/tags
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
32      ./.git/refs
68      ./.git/hooks
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/branches
16      ./.git/objects/74
8       ./.git/objects/fa
12      ./.git/objects/af
8       ./.git/objects/83
8       ./.git/objects/96
8       ./.git/objects/c0
8       ./.git/objects/93
12      ./.git/objects/17
8       ./.git/objects/24
8       ./.git/objects/1b
8       ./.git/objects/d8
12      ./.git/objects/14
12      ./.git/objects/70
8       ./.git/objects/0b
8       ./.git/objects/47
8       ./.git/objects/cd
12      ./.git/objects/44
12      ./.git/objects/72
8       ./.git/objects/e9
8       ./.git/objects/71
12      ./.git/objects/64
16      ./.git/objects/fb
8       ./.git/objects/a3
8       ./.git/objects/0d
8       ./.git/objects/c3
12      ./.git/objects/2e
8       ./.git/objects/7b
8       ./.git/objects/04
8       ./.git/objects/91
12      ./.git/objects/62
12      ./.git/objects/3d
12      ./.git/objects/1c
8       ./.git/objects/f6
8       ./.git/objects/b6
8       ./.git/objects/4f
8       ./.git/objects/fe
4       ./.git/objects/info
8       ./.git/objects/eb
8       ./.git/objects/41
12      ./.git/objects/29
8       ./.git/objects/e7
8       ./.git/objects/fc
8       ./.git/objects/4b
8       ./.git/objects/d7
8       ./.git/objects/b2
8       ./.git/objects/20
8       ./.git/objects/ab
12      ./.git/objects/73
8       ./.git/objects/52
8       ./.git/objects/c6
1828    ./.git/objects/pack
8       ./.git/objects/86
12      ./.git/objects/e5
8       ./.git/objects/58
8       ./.git/objects/f2
8       ./.git/objects/a4
12      ./.git/objects/6e
8       ./.git/objects/49
8       ./.git/objects/fd
8       ./.git/objects/81
8       ./.git/objects/3f
8       ./.git/objects/4a
8       ./.git/objects/a6
8       ./.git/objects/b9
8       ./.git/objects/3a
12      ./.git/objects/ff
8       ./.git/objects/23
12      ./.git/objects/b5
12      ./.git/objects/d2
8       ./.git/objects/60
8       ./.git/objects/cb
2476    ./.git/objects
8       ./.git/logs/refs/heads
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
28      ./.git/logs/refs
36      ./.git/logs
2668    ./.git
4       ./myroot/.local/share/nano
8       ./myroot/.local/share
12      ./myroot/.local
24      ./myroot
28      ./nodejs-app/node_modules/content-type
12      ./nodejs-app/node_modules/sqlstring/lib
40      ./nodejs-app/node_modules/sqlstring
28      ./nodejs-app/node_modules/statuses
8       ./nodejs-app/node_modules/get-proto/test
8       ./nodejs-app/node_modules/get-proto/.github
72      ./nodejs-app/node_modules/get-proto
8       ./nodejs-app/node_modules/depd/lib/browser
12      ./nodejs-app/node_modules/depd/lib
52      ./nodejs-app/node_modules/depd
40      ./nodejs-app/node_modules/serve-static
48      ./nodejs-app/node_modules/safe-buffer
8       ./nodejs-app/node_modules/side-channel-list/test
8       ./nodejs-app/node_modules/side-channel-list/.github
64      ./nodejs-app/node_modules/side-channel-list
20      ./nodejs-app/node_modules/encodeurl
24      ./nodejs-app/node_modules/methods
20      ./nodejs-app/node_modules/array-flatten
8       ./nodejs-app/node_modules/hasown/.github
48      ./nodejs-app/node_modules/hasown
8       ./nodejs-app/node_modules/side-channel-map/test
8       ./nodejs-app/node_modules/side-channel-map/.github
60      ./nodejs-app/node_modules/side-channel-map
32      ./nodejs-app/node_modules/proxy-addr
24      ./nodejs-app/node_modules/cookie-signature
12      ./nodejs-app/node_modules/mime/src
80      ./nodejs-app/node_modules/mime
24      ./nodejs-app/node_modules/vary
16      ./nodejs-app/node_modules/dunder-proto/test
8       ./nodejs-app/node_modules/dunder-proto/.github
72      ./nodejs-app/node_modules/dunder-proto
8       ./nodejs-app/node_modules/call-bind-apply-helpers/test
8       ./nodejs-app/node_modules/call-bind-apply-helpers/.github
96      ./nodejs-app/node_modules/call-bind-apply-helpers
28      ./nodejs-app/node_modules/media-typer
36      ./nodejs-app/node_modules/isarray
24      ./nodejs-app/node_modules/forwarded
8       ./nodejs-app/node_modules/es-object-atoms/test
8       ./nodejs-app/node_modules/es-object-atoms/.github
76      ./nodejs-app/node_modules/es-object-atoms
28      ./nodejs-app/node_modules/body-parser/lib/types
40      ./nodejs-app/node_modules/body-parser/lib
100     ./nodejs-app/node_modules/body-parser
232     ./nodejs-app/node_modules/iconv-lite/encodings/tables
348     ./nodejs-app/node_modules/iconv-lite/encodings
36      ./nodejs-app/node_modules/iconv-lite/lib
412     ./nodejs-app/node_modules/iconv-lite
36      ./nodejs-app/node_modules/content-disposition
4       ./nodejs-app/node_modules/.bin
24      ./nodejs-app/node_modules/destroy
20      ./nodejs-app/node_modules/escape-html
44      ./nodejs-app/node_modules/raw-body
32      ./nodejs-app/node_modules/express/lib/router
12      ./nodejs-app/node_modules/express/lib/middleware
128     ./nodejs-app/node_modules/express/lib
272     ./nodejs-app/node_modules/express
20      ./nodejs-app/node_modules/object-inspect/example
8       ./nodejs-app/node_modules/object-inspect/test/browser
96      ./nodejs-app/node_modules/object-inspect/test
8       ./nodejs-app/node_modules/object-inspect/.github
216     ./nodejs-app/node_modules/object-inspect
8       ./nodejs-app/node_modules/call-bound/test
8       ./nodejs-app/node_modules/call-bound/.github
56      ./nodejs-app/node_modules/call-bound
32      ./nodejs-app/node_modules/http-errors
8       ./nodejs-app/node_modules/readable-stream/doc/wg-meetings
12      ./nodejs-app/node_modules/readable-stream/doc
20      ./nodejs-app/node_modules/readable-stream/lib/internal/streams
24      ./nodejs-app/node_modules/readable-stream/lib/internal
96      ./nodejs-app/node_modules/readable-stream/lib
48      ./nodejs-app/node_modules/readable-stream/node_modules/safe-buffer
52      ./nodejs-app/node_modules/readable-stream/node_modules
224     ./nodejs-app/node_modules/readable-stream
16      ./nodejs-app/node_modules/string_decoder/lib
48      ./nodejs-app/node_modules/string_decoder/node_modules/safe-buffer
52      ./nodejs-app/node_modules/string_decoder/node_modules
88      ./nodejs-app/node_modules/string_decoder
32      ./nodejs-app/node_modules/mime-types
24      ./nodejs-app/node_modules/inherits
8       ./nodejs-app/node_modules/setprototypeof/test
32      ./nodejs-app/node_modules/setprototypeof
16      ./nodejs-app/node_modules/get-intrinsic/test
8       ./nodejs-app/node_modules/get-intrinsic/.github
80      ./nodejs-app/node_modules/get-intrinsic
24      ./nodejs-app/node_modules/send/node_modules/encodeurl
20      ./nodejs-app/node_modules/send/node_modules/ms
48      ./nodejs-app/node_modules/send/node_modules
116     ./nodejs-app/node_modules/send
28      ./nodejs-app/node_modules/ipaddr.js/lib
64      ./nodejs-app/node_modules/ipaddr.js
28      ./nodejs-app/node_modules/math-intrinsics/constants
12      ./nodejs-app/node_modules/math-intrinsics/test
8       ./nodejs-app/node_modules/math-intrinsics/.github
172     ./nodejs-app/node_modules/math-intrinsics
24      ./nodejs-app/node_modules/fresh
8       ./nodejs-app/node_modules/core-util-is/lib
24      ./nodejs-app/node_modules/core-util-is
24      ./nodejs-app/node_modules/merge-descriptors
52      ./nodejs-app/node_modules/qs/dist
120     ./nodejs-app/node_modules/qs/test
8       ./nodejs-app/node_modules/qs/.github
44      ./nodejs-app/node_modules/qs/lib
304     ./nodejs-app/node_modules/qs
8       ./nodejs-app/node_modules/side-channel/test
8       ./nodejs-app/node_modules/side-channel/.github
68      ./nodejs-app/node_modules/side-channel
20      ./nodejs-app/node_modules/process-nextick-args
36      ./nodejs-app/node_modules/accepts
220     ./nodejs-app/node_modules/mime-db
36      ./nodejs-app/node_modules/type-is
32      ./nodejs-app/node_modules/on-finished
20      ./nodejs-app/node_modules/ms
288     ./nodejs-app/node_modules/mysql/lib/protocol/constants
40      ./nodejs-app/node_modules/mysql/lib/protocol/sequences
100     ./nodejs-app/node_modules/mysql/lib/protocol/packets
496     ./nodejs-app/node_modules/mysql/lib/protocol
556     ./nodejs-app/node_modules/mysql/lib
48      ./nodejs-app/node_modules/mysql/node_modules/safe-buffer
52      ./nodejs-app/node_modules/mysql/node_modules
712     ./nodejs-app/node_modules/mysql
24      ./nodejs-app/node_modules/unpipe
40      ./nodejs-app/node_modules/finalhandler
24      ./nodejs-app/node_modules/toidentifier
20      ./nodejs-app/node_modules/path-to-regexp
64      ./nodejs-app/node_modules/safer-buffer
8       ./nodejs-app/node_modules/side-channel-weakmap/test
8       ./nodejs-app/node_modules/side-channel-weakmap/.github
60      ./nodejs-app/node_modules/side-channel-weakmap
12      ./nodejs-app/node_modules/has-symbols/test/shams
24      ./nodejs-app/node_modules/has-symbols/test
8       ./nodejs-app/node_modules/has-symbols/.github
88      ./nodejs-app/node_modules/has-symbols
24      ./nodejs-app/node_modules/negotiator/lib
52      ./nodejs-app/node_modules/negotiator
28      ./nodejs-app/node_modules/bytes
36      ./nodejs-app/node_modules/debug/src
112     ./nodejs-app/node_modules/debug
28      ./nodejs-app/node_modules/etag
20      ./nodejs-app/node_modules/function-bind/test
12      ./nodejs-app/node_modules/function-bind/.github
80      ./nodejs-app/node_modules/function-bind
24      ./nodejs-app/node_modules/parseurl
20      ./nodejs-app/node_modules/ee-first
24      ./nodejs-app/node_modules/utils-merge
8       ./nodejs-app/node_modules/es-define-property/test
8       ./nodejs-app/node_modules/es-define-property/.github
56      ./nodejs-app/node_modules/es-define-property
92      ./nodejs-app/node_modules/bignumber.js/doc
420     ./nodejs-app/node_modules/bignumber.js
28      ./nodejs-app/node_modules/util-deprecate
8       ./nodejs-app/node_modules/gopd/test
8       ./nodejs-app/node_modules/gopd/.github
60      ./nodejs-app/node_modules/gopd
36      ./nodejs-app/node_modules/cookie
8       ./nodejs-app/node_modules/es-errors/test
8       ./nodejs-app/node_modules/es-errors/.github
100     ./nodejs-app/node_modules/es-errors
24      ./nodejs-app/node_modules/range-parser
6056    ./nodejs-app/node_modules
6108    ./nodejs-app
1972    ./images
10804   .
```
5. Run the command **ls** . ***(1 mark)***
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ ls
README.md  images  myroot  nodejs-app  webpage
```
6. Run the command **ls -asl** . ***(1 mark)*** 
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ ls -asl
total 60
 4 drwxrwxrwx+ 7 codespace root       4096 Jan 30 07:12 .
 4 drwxr-xrwx+ 5 codespace root       4096 Jan 30 05:03 ..
 4 drwxrwxrwx+ 9 codespace root       4096 Jan 30 05:07 .git
32 -rw-rw-rw-  1 codespace root      28835 Jan 30 08:40 README.md
 4 drwxrwxrwx+ 2 codespace root       4096 Jan 30 05:03 images
 4 drwxrwxrwx+ 3 codespace codespace  4096 Jan 30 06:44 myroot
 4 drwxrwxrwx+ 3 codespace codespace  4096 Jan 30 07:18 nodejs-app
 4 drwxrwxrwx+ 2 codespace codespace  4096 Jan 30 06:52 webpage
```
7. Run the command **free -h** . ***(1 mark)***
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.3Gi       267Mi        59Mi       6.2Gi       6.1Gi
```
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3240.688
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
bogomips        : 4890.86
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
cpu MHz         : 3083.213
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
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```
9. Run the command **top** and type **q** to quit. ***(1 mark)***
```bash
processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3083.213
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
top - 08:44:11 up 12 min,  0 users,  load average: 0.17, 0.72, 0.77
Tasks:  21 total,   1 running,  20 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.0 us, 17.2 sy,  0.0 ni, 82.8 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    314.5 free,   1325.2 used,   6289.9 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6228.6 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                
    923 codespa+  20   0   41.5g 323380  51072 S   6.7   4.0   0:27.19 node                                                                                   
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.03 docker-init                                                                            
      7 codespa+  20   0    7236   1792   1792 S   0.0   0.0   0:00.02 sleep                                                                                  
     35 root      20   0   12196   3480   2560 S   0.0   0.0   0:00.00 sshd                                                                                   
    685 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.01 sh                                                                                     
    712 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                                                                     
    875 codespa+  20   0    2624   1536   1536 S   0.0   0.0   0:00.01 sh                                                                                     
    884 codespa+  20   0   11.3g  94576  47616 S   0.0   1.2   0:03.59 node                                                                                   
    936 codespa+  20   0   11.2g  54108  43648 S   0.0   0.7   0:00.27 node                                                                                   
   1375 codespa+  20   0   11.1g  67280  44544 S   0.0   0.8   0:00.97 node                                                                                   
   1386 codespa+  20   0 1011448  63436  41600 S   0.0   0.8   0:02.82 node                                                                                   
   1394 codespa+  20   0   16812  11648   3328 S   0.0   0.1   0:00.17 bash
```
10. Run the command **uname -a**. ***(1 mark)*** 
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-8197f1 6.5.0-1025-azure #26~22.04.1-Ubuntu SMP Thu Jul 11 22:33:04 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. ***(1 mark)*** __218 Mi__.
12. What is the available disk space mounted on /workspace. ***(1 mark)*** __20772600__.
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __Linux codespaces-b10985 6.5.0-1022-azure #23~22.04.1-Ubuntu SMP Thu May 9 17:59:24 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux__.
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __ls -asl provides more detailed information, including block usage, while ls gives a simpler listing of files and directories12__.
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __2560 4K pages__.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __2560 4K pages__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __2560 4K pages__.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker pull debian
Using default tag: latest
latest: Pulling from library/debian
fea1432adf09: Pull complete 
Digest: sha256:a92ed51e0996d8e9de041ca05ce623d2c491444df6a535a566dabd5cb8336946
Status: Downloaded newer image for debian:latest
docker.io/library/debian:latest

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker run --detach -it debian
984e12f953ef232176ab7de2679567dd677a131dcf334787b588ac79683e964b
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
136e67b8d7b5   debian    "bash"    12 minutes ago   Up 12 minutes             admiring_lovelace
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```
```bash
docker exec -i -t admiring_lovelace /bin/bash
```
4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.
```bash
root@136e67b8d7b5:/# apt-get update 
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8786 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [164 kB]
Fetched 9218 kB in 1s (8718 kB/s)                         
Reading package lists... Done

root@136e67b8d7b5:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (31.1 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...

root@136e67b8d7b5:/# cd /root

root@136e67b8d7b5:~# nano helloworld.txt

```

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker stop admiring_lovelace
admiring_lovelace

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                       PORTS     NAMES
136e67b8d7b5   debian    "bash"    47 minutes ago   Exited (137) 8 seconds ago             admiring_lovelace

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker restart admiring_lovelace
admiring_lovelace

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker exec -i -t admiring_lovelace /bin/bash
root@ec38e09f71b5:/# cd root
root@ec38e09f71b5:~# ls
helloworld.txt
root@ec38e09f71b5:~# cat helloworld.txt
HELLO WORLD !!

```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker stop admiring_lovelace
admiring_lovelace

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                       PORTS     NAMES
136e67b8d7b5   debian    "bash"    48 minutes ago   Exited (137) 8 seconds ago             admiring_lovelace

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker rm admiring_lovelace
admiring_lovelace
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __It is not consistent because the files is removed when the container is removed__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Yes, we can run multiple instances of Debian Linux on the same physical or virtual machine__.

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
6423e4a32316   debian    "bash"    7 seconds ago   Up 5 seconds             happy_torvalds
ec38e09f71b5   debian    "bash"    8 minutes ago   Up 4 minutes             eager_perlman

```

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
```bash
@musanna ➜ /workspaces/OSProject (main) $ mkdir myroot
@musanna ➜ /workspaces/OSProject (main) $ cd myroot/
@musanna ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot
@musanna ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
cc179da0e1d2e4c8d24b3ae3d965bca274687f84d061a19449ac15c28aeebe26
@musanna ➜ /workspaces/OSProject/myroot (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
cc179da0e1d2   debian    "bash"    24 seconds ago   Up 22 seconds             pensive_northcutt
@musanna ➜ /workspaces/OSProject/myroot (main) $ docker exec -i -t pensive_northcutt /bin/bash
root@cc179da0e1d2:/# cd /root
root@cc179da0e1d2:~# nano helloworld.txt
root@cc179da0e1d2:~# ls
helloworld.txt
root@cc179da0e1d2:~# exit
exit
@musanna ➜ /workspaces/OSProject/myroot (main) $ ls
helloworld.txt

```
***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __root__.
```bash
@salman ➜ /workspaces/OSProject/myroot (main) $ ls -la
total 16
drwxrwxrwx+ 3 codespace codespace 4096 Jun 29 13:19 .
drwxrwxrwx+ 5 codespace root      4096 Jun 29 02:31 ..
drwxrwxrwx+ 3 root      root      4096 Jun 29 10:13 .local
-rw-rw-rw-  1 root      root        13 Jun 29 13:14 helloworld.txt
```
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** YES.***
```bash
@salman ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace helloworld.txt
@salman ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace .local
@salman ➜ /workspaces/OSProject/myroot (main) $ ls -la
total 16
drwxrwxrwx+ 3 codespace codespace 4096 Jun 29 13:19 .
drwxrwxrwx+ 5 codespace root      4096 Jun 29 02:31 ..
drwxrwxrwx+ 3 codespace codespace 4096 Jun 29 10:13 .local
-rw-rw-rw-  1 codespace codespace   13 Jun 29 13:14 helloworld.txt
```

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

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 
```bash
@tanvir ➜ /workspaces/OSProject/webpage (main) $ ls -ld /workspaces/OSProject/webpage
drwxrwxrwx+ 2 codespace codespace 4096 Jun 29 07:51 /workspaces/OSProject/webpage
```
2. What port is the apache web server running. ***(1 mark)*** __80__
3. What port is open for http protocol on the host machine? ***(1 mark)*** __8080__

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


```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker network create bluenet
eee3476aac1a1d55ddd9bb7443a70867607024fa390a5e559a8d9664a4db8f19

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker network create rednet
bc2b764e3ae24e741f5f8e1ae238f4f08af6a1ec7b673f62e55ace40fe7dd206

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker run -itd --net bluenet --name c1 busybox sh
Unable to find image 'busybox:latest' locally
latest: Pulling from library/busybox
ec562eabd705: Pull complete 
Digest: sha256:9ae97d36d26566ff84e8893c64a6dc4fe8ca6d1144bf5b87b2b85a32def253c7
Status: Downloaded newer image for busybox:latest
4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker run -itd --net rednet --name c2 busybox sh
7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef

```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __FBusybox is a software that combines several common Unix utilities into a single executable and '--name' allows us to specify a meaningful or identifiable name for easier management and reference__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
eee3476aac1a   bluenet   bridge    local
8b5f9f2f8207   bridge    bridge    local
d50c26ba34c1   host      host      local
110b5300ed10   none      null      local
bc2b764e3ae2   rednet    bridge    local
```
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
```
bluenet: "Gateway": "172.18.0.1",
rednet: "Gateway": "172.19.0.1",
```
```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker inspect c1
[
    {
        "Id": "4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f",
        "Created": "2024-06-28T19:46:18.548515881Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 8596,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-06-28T19:46:19.379634709Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f/hostname",
        "HostsPath": "/var/lib/docker/containers/4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f/hosts",
        "LogPath": "/var/lib/docker/containers/4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f/4ea1ff0050bc21903a9320d851ac5ee3092be2296412ec087e2e6f74ec8d9e0f-json.log",
        "Name": "/c1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "bluenet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                9,
                127
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/915a39e05d53a814eadc52094ad37f53fbb71c8a97cd2b29392f3382c8401b27-init/diff:/var/lib/docker/overlay2/05f3403eaf634e627c82ccafd4b83898e6412b7695937ea15644214916c8eeeb/diff",
                "MergedDir": "/var/lib/docker/overlay2/915a39e05d53a814eadc52094ad37f53fbb71c8a97cd2b29392f3382c8401b27/merged",
                "UpperDir": "/var/lib/docker/overlay2/915a39e05d53a814eadc52094ad37f53fbb71c8a97cd2b29392f3382c8401b27/diff",
                "WorkDir": "/var/lib/docker/overlay2/915a39e05d53a814eadc52094ad37f53fbb71c8a97cd2b29392f3382c8401b27/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "4ea1ff0050bc",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "64aa66e73028c635d8519144faf31e74dfce982303f6a58bdc6d959ce845996f",
            "SandboxKey": "/var/run/docker/netns/64aa66e73028",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "bluenet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:12:00:02",
                    "NetworkID": "eee3476aac1a1d55ddd9bb7443a70867607024fa390a5e559a8d9664a4db8f19",
                    "EndpointID": "2c3942c5539118344db54666101513c1adf2b1e7e9dfda6c5ca7a38da7f9ce36",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c1",
                        "4ea1ff0050bc"
                    ]
                }
            }
        }
    }
]
```

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker inspect c2
[
    {
        "Id": "7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef",
        "Created": "2024-06-28T19:46:27.593732797Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 8786,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-06-28T19:46:28.077825393Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef/hostname",
        "HostsPath": "/var/lib/docker/containers/7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef/hosts",
        "LogPath": "/var/lib/docker/containers/7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef/7737cf19a8300ae17d3766bacf05cb30e048a5e2730dd8b235b127aaf67f35ef-json.log",
        "Name": "/c2",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "rednet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                9,
                127
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/806d35763aaf90593be992ff3d1544f839218b4b58b67d2e6aa9340577476f84-init/diff:/var/lib/docker/overlay2/05f3403eaf634e627c82ccafd4b83898e6412b7695937ea15644214916c8eeeb/diff",
                "MergedDir": "/var/lib/docker/overlay2/806d35763aaf90593be992ff3d1544f839218b4b58b67d2e6aa9340577476f84/merged",
                "UpperDir": "/var/lib/docker/overlay2/806d35763aaf90593be992ff3d1544f839218b4b58b67d2e6aa9340577476f84/diff",
                "WorkDir": "/var/lib/docker/overlay2/806d35763aaf90593be992ff3d1544f839218b4b58b67d2e6aa9340577476f84/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "7737cf19a830",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "8fbf76bdc859bc71a3f1faf3a88f3e7b8410d319a9448d1e269693668233708f",
            "SandboxKey": "/var/run/docker/netns/8fbf76bdc859",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "rednet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:13:00:02",
                    "NetworkID": "bc2b764e3ae24e741f5f8e1ae238f4f08af6a1ec7b673f62e55ace40fe7dd206",
                    "EndpointID": "28b059dc9ed4866946d884be98c6a72e8749021022a9253ece82137b9f23a144",
                    "Gateway": "172.19.0.1",
                    "IPAddress": "172.19.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c2",
                        "7737cf19a830"
                    ]
                }
            }
        }
    }
]
```
4. What is the network address for the running container c1 and c2? ***(1 mark)***
```
c1 = "IPAddress": "172.18.0.2"
c2 = "IPAddress": "172.19.0.2"
```

5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** __Not able to ping__.

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** __Yes__.

```bash
@musanna ➜ /workspaces/OSProject (main) $ docker network create bridgenet
154d0a3f320efb2102874e817f6872a541d8da903d4978cc759cbd96bead8113
@musanna ➜ /workspaces/OSProject (main) $ docker network connect bridgenet c1
@musanna ➜ /workspaces/OSProject (main) $ docker network connect bridgenet c2
@musanna ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
PING c2 (172.21.0.3): 56 data bytes
64 bytes from 172.21.0.3: seq=0 ttl=64 time=0.138 ms
64 bytes from 172.21.0.3: seq=1 ttl=64 time=0.065 ms
64 bytes from 172.21.0.3: seq=2 ttl=64 time=0.067 ms
64 bytes from 172.21.0.3: seq=3 ttl=64 time=0.064 ms
64 bytes from 172.21.0.3: seq=4 ttl=64 time=0.081 ms
64 bytes from 172.21.0.3: seq=5 ttl=64 time=0.062 ms
64 bytes from 172.21.0.3: seq=6 ttl=64 time=0.108 ms
64 bytes from 172.21.0.3: seq=7 ttl=64 time=0.057 ms
64 bytes from 172.21.0.3: seq=8 ttl=64 time=0.078 ms
64 bytes from 172.21.0.3: seq=9 ttl=64 time=0.062 ms
64 bytes from 172.21.0.3: seq=10 ttl=64 time=0.065 ms
64 bytes from 172.21.0.3: seq=11 ttl=64 time=0.067 ms
64 bytes from 172.21.0.3: seq=12 ttl=64 time=0.061 ms
64 bytes from 172.21.0.3: seq=13 ttl=64 time=0.068 ms
64 bytes from 172.21.0.3: seq=14 ttl=64 time=0.067 ms
64 bytes from 172.21.0.3: seq=15 ttl=64 time=0.067 ms
64 bytes from 172.21.0.3: seq=16 ttl=64 time=0.071 ms
64 bytes from 172.21.0.3: seq=17 ttl=64 time=0.075 ms
64 bytes from 172.21.0.3: seq=18 ttl=64 time=0.060 ms
64 bytes from 172.21.0.3: seq=19 ttl=64 time=0.059 ms
64 bytes from 172.21.0.3: seq=20 ttl=64 time=0.052 ms
64 bytes from 172.21.0.3: seq=21 ttl=64 time=0.072 ms
64 bytes from 172.21.0.3: seq=22 ttl=64 time=0.062 ms
64 bytes from 172.21.0.3: seq=23 ttl=64 time=0.066 ms
64 bytes from 172.21.0.3: seq=24 ttl=64 time=0.076 ms
64 bytes from 172.21.0.3: seq=25 ttl=64 time=0.061 ms
64 bytes from 172.21.0.3: seq=26 ttl=64 time=0.084 ms
64 bytes from 172.21.0.3: seq=27 ttl=64 time=0.066 ms
64 bytes from 172.21.0.3: seq=28 ttl=64 time=0.063 ms
64 bytes from 172.21.0.3: seq=29 ttl=64 time=0.060 ms
64 bytes from 172.21.0.3: seq=30 ttl=64 time=0.050 ms
64 bytes from 172.21.0.3: seq=31 ttl=64 time=0.078 ms
64 bytes from 172.21.0.3: seq=32 ttl=64 time=0.056 ms
64 bytes from 172.21.0.3: seq=33 ttl=64 time=0.054 ms
64 bytes from 172.21.0.3: seq=34 ttl=64 time=0.081 ms
64 bytes from 172.21.0.3: seq=35 ttl=64 time=0.052 ms
64 bytes from 172.21.0.3: seq=36 ttl=64 time=0.081 ms
64 bytes from 172.21.0.3: seq=37 ttl=64 time=0.065 ms
64 bytes from 172.21.0.3: seq=38 ttl=64 time=0.071 ms
64 bytes from 172.21.0.3: seq=39 ttl=64 time=0.062 ms
64 bytes from 172.21.0.3: seq=40 ttl=64 time=0.053 ms
64 bytes from 172.21.0.3: seq=41 ttl=64 time=0.063 ms
64 bytes from 172.21.0.3: seq=42 ttl=64 time=0.083 ms
64 bytes from 172.21.0.3: seq=43 ttl=64 time=0.066 ms
64 bytes from 172.21.0.3: seq=44 ttl=64 time=0.070 ms
64 bytes from 172.21.0.3: seq=45 ttl=64 time=0.069 ms
64 bytes from 172.21.0.3: seq=46 ttl=64 time=0.056 ms
64 bytes from 172.21.0.3: seq=47 ttl=64 time=0.062 ms
64 bytes from 172.21.0.3: seq=48 ttl=64 time=0.086 ms
64 bytes from 172.21.0.3: seq=49 ttl=64 time=0.065 ms
64 bytes from 172.21.0.3: seq=50 ttl=64 time=0.060 ms

```
2. What is different from the previous ping in the section above? ***(1 mark)*** __The 2 networks are now connected properly, making c1 unable to ping c2__.

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker network create mysqlnet
5efad54fbe7fbcc345455fd9147537fd7955d088a321c5f2a0fc564f14b61622

@Tasmiahub ➜ /workspaces/OSProject (main) $ docker network create nodejsnet
03f11a6e0f798ad0613862a57bf68053e5f519884833f6437a373cbd67e4f8db
```

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

```bash
@Tasmiahub ➜ /workspaces/OSProject (main) $ docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
Unable to find image 'mysql:latest' locally
latest: Pulling from library/mysql
7af76bb36546: Pull complete 
24d40f69285f: Pull complete 
94e5412f594e: Pull complete 
e00a64de64e9: Pull complete 
e3dd3d47ce6c: Pull complete 
18af3efb629d: Pull complete 
ba3db9dfd86e: Pull complete 
787130cbc394: Pull complete 
d458a2361496: Pull complete 
d48f1878172c: Pull complete 
Digest: sha256:dab7049abafe3a0e12cbe5e49050cf149881c0cd9665c289e5808b9dad39c9e0
Status: Downloaded newer image for mysql:latest
c73e677f3862fda8f3a68d9845c9d9e12f9e0ffa504863dbc94af388974fe75b
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

```bash
 @tanvir ➜ /workspaces/OSProject (main) $ mkdir nodejs-app

@tanvir ➜ /workspaces/OSProject (main) $ cd nodejs-app
@tanvir ➜ /workspaces/OSProject/nodejs-app (main) $ npm init -y
Wrote to /workspaces/OSProject/nodejs-app/package.json:

{
  "name": "nodejs-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.19.2",
    "mysql": "^2.18.1"
  },
  "devDependencies": {},
  "description": ""
}
@tanvir ➜ /workspaces/OSProject/nodejs-app (main) $ npm install express mysql

up to date, audited 77 packages in 1s

12 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities



    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```
```bash

@tanvir ➜ /workspaces/OSProject/nodejs-app (main) $ nano index.js


Use "fg" to return to nano.

[1]+  Stopped                 nano index.js

```
3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

```bash

@tanvir ➜ /workspaces/OSProject/nodejs-app (main) $ nano dockerfile


Use "fg" to return to nano.

[2]+  Stopped                 nano dockerfile
```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```
```sh
@musanna ➜ /workspaces/OSProject/nodejs-app (main) $ docker build -t nodejs-app .
[+] Building 34.5s (11/11) FINISHED                                                                                                            docker:default
=> [internal] load build definition from Dockerfile                                                                                                     0.2s
=> => transferring dockerfile: 407B                                                                                                                     0.0s
=> [internal] load metadata for docker.io/library/node:14                                                                                               3.0s
=> [auth] library/node:pull token for registry-1.docker.io                                                                                              0.0s
=> [internal] load .dockerignore                                                                                                                        0.1s
=> => transferring context: 2B                                                                                                                          0.0s
=> [1/5] FROM docker.io/library/node:14@sha256:a158d3b9b4e3fa813fa6c8c590b8f0a860e015ad4e59bbce5744d2f6fd8461aa                                        21.5s
=> => resolve docker.io/library/node:14@sha256:a158d3b9b4e3fa813fa6c8c590b8f0a860e015ad4e59bbce5744d2f6fd8461aa                                         0.2s
=> => sha256:2cafa3fbb0b6529ee4726b4f599ec27ee557ea3dea7019182323b3779959927f 2.21kB / 2.21kB                                                           0.0s
=> => sha256:a158d3b9b4e3fa813fa6c8c590b8f0a860e015ad4e59bbce5744d2f6fd8461aa 776B / 776B                                                               0.0s
=> => sha256:1d12470fa662a2a5cb50378dcdc8ea228c1735747db410bbefb8e2d9144b5452 7.51kB / 7.51kB                                                           0.0s
=> => sha256:b253aeafeaa7e0671bb60008df01de101a38a045ff7bc656e3b0fbfc7c05cca5 7.86MB / 7.86MB                                                           0.7s
=> => sha256:2ff1d7c41c74a25258bfa6f0b8adb0a727f84518f55f65ca845ebc747976c408 50.45MB / 50.45MB                                                         0.9s
=> => sha256:3d2201bd995cccf12851a50820de03d34a17011dcbb9ac9fdf3a50c952cbb131 10.00MB / 10.00MB                                                         1.1s
=> => extracting sha256:2ff1d7c41c74a25258bfa6f0b8adb0a727f84518f55f65ca845ebc747976c408                                                                2.9s
=> => sha256:1de76e268b103d05fa8960e0f77951ff54b912b63429c34f5d6adfd09f5f9ee2 51.88MB / 51.88MB                                                         2.1s
=> => sha256:d9a8df5894511ce28a05e2925a75e8a4acbd0634c39ad734fdfba8e23d1b1569 191.85MB / 191.85MB                                                       3.9s
=> => sha256:6f51ee005deac0d99898e41b8ce60ebf250ebe1a31a0b03f613aec6bbc9b83d8 4.19kB / 4.19kB                                                           1.4s
=> => sha256:5f32ed3c3f278edda4fc571c880b5277355a29ae8f52b52cdf865f058378a590 35.24MB / 35.24MB                                                         2.3s
=> => sha256:0c8cc2f24a4dcb64e602e086fc9446b0a541e8acd9ad72d2e90df3ba22f158b3 2.29MB / 2.29MB                                                           2.5s
=> => sha256:0d27a8e861329007574c6766fba946d48e20d2c8e964e873de352603f22c4ceb 450B / 450B                                                               2.6s
=> => extracting sha256:b253aeafeaa7e0671bb60008df01de101a38a045ff7bc656e3b0fbfc7c05cca5                                                                0.3s
=> => extracting sha256:3d2201bd995cccf12851a50820de03d34a17011dcbb9ac9fdf3a50c952cbb131                                                                0.2s
=> => extracting sha256:1de76e268b103d05fa8960e0f77951ff54b912b63429c34f5d6adfd09f5f9ee2                                                                2.3s
=> => extracting sha256:d9a8df5894511ce28a05e2925a75e8a4acbd0634c39ad734fdfba8e23d1b1569                                                                6.6s
=> => extracting sha256:6f51ee005deac0d99898e41b8ce60ebf250ebe1a31a0b03f613aec6bbc9b83d8                                                                0.0s
=> => extracting sha256:5f32ed3c3f278edda4fc571c880b5277355a29ae8f52b52cdf865f058378a590                                                                2.0s
=> => extracting sha256:0c8cc2f24a4dcb64e602e086fc9446b0a541e8acd9ad72d2e90df3ba22f158b3                                                                0.1s
=> => extracting sha256:0d27a8e861329007574c6766fba946d48e20d2c8e964e873de352603f22c4ceb                                                                0.0s
=> [internal] load build context                                                                                                                        0.5s
=> => transferring context: 3.35MB                                                                                                                      0.2s
=> [2/5] WORKDIR /usr/src/app                                                                                                                           0.2s
=> [3/5] COPY package*.json ./                                                                                                                          0.2s
=> [4/5] RUN npm install                                                                                                                                3.5s
=> [5/5] COPY . .                                                                                                                                       0.5s
=> exporting to image                                                                                                                                   4.7s
=> => exporting layers                                                                                                                                  4.6s
=> => writing image sha256:092c7ca1d7646f824646e53c9d02b526f37b8b6bcef8058b015cfed2cc503ae8                                                             0.0s
=> => naming to docker.io/library/nodejs-app
```
2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```
```bash
@musanna ➜ /workspaces/OSProject/nodejs-app (main) $ docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
00f23182728ddc7f819b3e107a3a682afaee95529f32f7c8e8d77ed9146d8288
```
#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** __Fill answer here__.
```bash
@Tasmiahub ➜ /workspaces/OSProject/nodejs-app (main) $ curl http://localhost:3000/random
curl: (7) Failed to connect to localhost port 3000: Connection refused

it is error because the node.js container cannot reach the MySQL container by its hostname mysql container until the networks are bridged.

```
2. Show the instruction needed to make this work. ***(1 mark)*** __Fill answer here__.

```bash

docker network connect mysqlnet nodejs-container

```



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
