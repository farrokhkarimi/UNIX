# Unix tutorial
![PC](https://opensource.com/sites/default/files/u128651/ibm_pc_at.jpg)

# Headlines
- UNIX branches
- Linux distributions
- System boot + grub + swap + MBR and GPT
- Installation + Dual boot + Virtualization + Cloud
- Filesystem
- Commands
- Hardware info
- File management
- Package management
- Process management
- System management
- Network
- Remote

## Basic commands
* man # an interface to the on-line reference manuals
* lsb_release # print distribution-specific information
* uname # print system information
* whoami # print effective userid
* passwd # change user password
* date # print or set the system date and time
* cal # displays a calendar and the date of Easter
* users # print the user names of users currently logged in to the current host
* who # show who is logged on
* history # GNU History Library
* bash # GNU Bourne-Again SHell
* exit # cause normal process termination

## Hardware info
* lshw # list hardware
* lscpu # display information about the CPU architecture
* lsusb # list USB devices
* lspci # list all PCI devices
* hardinfo # System profiler and benchmark for Linux systems
* gparted # GNOME Partition Editor for manipulating disk partitions (sudoers)
* tree -L 1 / # list contents of directories in a tree-like format
* du # estimate file space usage
* df # report file system disk space usage

## File management
* pwd # print name of current/working directory
* ls # list directory contents (also ll)
* mkdir # make directories
* touch # change file timestamps (creating files)
* nano # Nano's ANOther editor, an enhanced free Pico clone
* cat # concatenate files and print on the standard output
* head # output the first part of files
* tail # output the last part of files
* chown # change file owner and group
* chmod # change file mode bits
* cp # copy files and directories
* mv # move (rename) files
* rm # remove files or directories
* locate # find files by name
* find # search for files in a directory hierarchy
* wc # print newline, word, and byte counts for each file
* echo # display a line of text
* echo $PATH

## Package management
* apt # command-line interface for managing packages (formerly apt-get)
* apt update
* apt upgrade
* apt search
* apt install
* apt remove
* apt purge
* apt autoremove
* dpkg # package manager for Debian
* dpkg-reconfigure # reconfigure an already installed package
* aptitude # high-level interface to the package manager (a newer tool)
* snap # Tool to interact with snaps (a newer tool)

## Process management
* ps -aux # report a snapshot of the current processes
* top # display Linux processes
* htop # interactive process viewer
* kill # send a signal to a process
* killall # kill processes by name
* free # Display amount of free and used memory in the system
* nvidia-smi # NVIDIA System Management Interface program
* uptime # Tell how long the system has been running

## System management
* runlevel # Print previous and current SysV runlevel
* halt # halt the machine
* shutdown # power-off the machine
* reboot # reboot the machine
* init # systemd system and service manager
* systemctl # Control the systemd system and service manager

## Basic network commands
* ifconfig # configure a network interface
* ping # send ICMP ECHO_REQUEST to network hosts
* speedtest

## Advanced
* zip # package and compress (archive) files
* gzip # gunzip, zcat - compress or expand files
* tar # an archiving utility
* xeyes &

## Remote
* ssh username@host

**Thanks**

Author: Farokh Karimi [LinkedIn](https://www.linkedin.com/in/farrokhkarimi), [Instagram](https://www.instagram.com/farrokhkarimi)
