# Day-02 Task: Linux Architecture Notes

1. Linux Architecture is based on CLI(Command Line Interface) consisting of 3 layers:

   -> Applications - All the end-user interactive applications are there in the outermost layer of the linux architecture.

   -> Shell - A shell is an interactive way to communicate between the applications and the kernel using linux commands.

   -> Kernel - It is the innermost layer and the core of linux, which administers the hardware and all the functioning of the linux as an operating system.
      It helps communicate between applications and the hardware through the middle layer- shell.


3. Root directory (/) :

   -> It is the root(starting) directory of the linux operating system.

   -> It contains multiple directories and files which all comprises to form and run the linux operating system.

   -> bin - It stands for binaries.
      Shell Command --> C Program --> 01010001011 (binary language)

4. WORKING OF LINUX :

                           Operating System(Linux)
                                     |
                                     | (Power ON)
                                    \|/
           BIOS (Activates motherboard, which loads the hardware)
                                     |
                                    \|/  
        GNU GRUB (Grand Unified Bootloader) - loads the linux kernel
                                     |
                                    \|/
                         Operating System Loading...
                                     |
                                    \|/
         init process / systemd - first process generated with PID-1
                                     |
                                    \|/
                   systemctl (system controller command)
                      Example: systemctl start nginx
                               systemctl start docker
                               systemctl start ssh
                               systemctl status ssh


5. Some common linux commands are -

        -> touch hello.txt
        -> nano hello.txt (CTR + O, Enter, CTR + X)
        -> cat hello.txt
        -> top, htop
        -> ps a, ps aux, ps aux | grep <pattern>
        -> uname, uname -r
        -> pwd
        -> mv hello.txt intro.txt
        -> mv intro.txt ../devops
        -> mkdir josh-batch-10
        -> cp hello.txt ../devops-zero-to-hero
        -> man ps, man mkdir, man uname
        -> lsblk
