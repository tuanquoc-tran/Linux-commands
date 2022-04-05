# Linux-commands
Refer link: https://github.com/bobbyiliev Copyright by @bobbyiliev

# Content <!-- omit in toc -->

- [VI](#vi)

## VI
To leave editing mode press `ESC`.

| Command   | Description           |
| --------- | --------------------- |
| `i`       | insert before cursor  |
| `a`       | insert after cursor   |
| `A`       | insert at end of line |
| `o`       | new line below        |
| `O`       | new line above        |
| `u`       | undo                  |
| `.`       | repeat last command   |
| `yy`      | copy line             |
| `5yy`     | copy 5 lines          |
| `p`       | paste below           |
| `P`       | paste above           |
| `x`       | delete character      |
| `5x`      | delete 5 characters   |
| `dd`      | delete line           |
| `5dd`     | delete 5 lines        |
| `:10,20d` | delete lines 10-20    |
| `d0`      | delete to line begin  |
| `d$`      | delete to line end    |

**Navigation**

Navigate as usual with `arrow keys`, `home`, `end`, `pg up`, `pg dn`.

| Command | Description            |
| ------- | ---------------------- |
| `5G`    | go to line 5           |
| `H`     | go to top of screen    |
| `M`     | go to middle of screen |
| `L`     | go to end of screen    |
| `5w`    | move over 7 words      |
| `5b`    | move back 5 words      |

**Other**

| Command     | Description                  |
| ----------- | ---------------------------- |
| `/foo`      | search forward               |
| `?foo`      | search backwards             |
| `n`         | repeat search                |
| `:w`        | save                         |
| `:q`        | close                        |
| `:wq`       | save and close               |
| `:q!`       | close without saving         |
| `:!command` | run bash command             |
| `:r foo`    | read file foo into this file |
| :set number   | Absolute Line Numbers |



# 📃 List of commands by category:
---
### Directory Navigation

- [cd](ebook/en/content/002-the-cd-command.md) - change working directory
- [ls](ebook/en/content/001-the-ls-command.md) - list directory contents
- [dir](ebook/en/content/057-the-dir-command.md) - directory listing, columnar format
- [pwd](ebook/en/content/006-the-pwd-command.md) - return working directory name
- [tree](ebook/en/content/095-the-tree-command.md) - list subdirectories in a tree structure


### File Commands

- [cat/tac](ebook/en/content/003-the-cat-tac-command.md) - concatenate and print files
- [diff/sdiff](ebook/en/content/062-the-diff-sdiff-command.md) - compare files line by line
- [find](ebook/en/content/102-the-find-command.md) - search for files
- [grep](ebook/en/content/107-the-grep-command.md) - file pattern matcher
- [head](ebook/en/content/004-the-head-command.md) - display the first lines of a file
- [locate](ebook/en/content/049-the-locate-command.md) - find files and directories
- [stat](ebook/en/content/079-the-stat-command.md) - display file status
- [tail](ebook/en/content/005-the-tail-command.md) - display the last lines of a file
- [uniq](ebook/en/content/074-the-uniq-command.md) -  report or filter out repeated lines in a file

### File and Directory Manipulation

- [awk](ebook/en/content/090-the-awk-command.md) - pattern-directed scanning and processing language
- [chmod](ebook/en/content/106-the-chmod-command.md) - change permissions
- [chown](ebook/en/content/101-the-chown-command.md) - change file owner and group
- [cp](ebook/en/content/031-the-cp-command.md) - copy files and directories
- [cut](ebook/en/content/098-the-cut-command.md) - remove sections from files
- [mkdir](ebook/en/content/014-the-mkdir-command.md) - make a new directory
- [mv](ebook/en/content/032-the-mv-command.md) - move files and directories
- [nano](ebook/en/content/039-the-nano-command.md) - text editor
- [rm](ebook/en/content/040-the-rm-command.md) - delete files and directories
- [rmdir](ebook/en/content/103-the-rmdir-command.md) - remove directory
- [paste](ebook/en/content/060-the-paste-command.md) - merge corresponding or subsequent lines of file
- [rsync](ebook/en/content/086-the-rsync-command.md) - remote copy files
- [scp](ebook/en/content/076-the-scp-command.md) - secure copy
- [basename](ebook/en/content/111-the-basename-command.md) - strips directory information and suffixes from file path
- [sed](ebook/en/content/099-the-sed-command.md) - text transformation tool
- [sort](ebook/en/content/059-the-sort-command.md) - arrange or merge lines of files
- [split](ebook/en/content/078-the-split-command.md) - split a file into pieces
- [touch](ebook/en/content/007-the-touch-command.md) - change file access and modification times
- [vim](ebook/en/content/100-the-vim-command.md) - text editor

### Package archive and compression tools

- [bzip2](ebook/en/content/069-the-bzip2-command.md) - block-sorting file compressor
- [gzip](ebook/en/content/015-the-gzip-command.md) - compression tool
- [gunzip](ebook/en/content/064-the-gunzip-command.md) - decompression tool
- [tar](ebook/en/content/063-the-tar-command.md) - create, extract and manipulate archives
- [zip](ebook/en/content/054-the-zip-command.md) - package and compress files
- [unzip](ebook/en/content/055-the-unzip-command.md) - list, test, extract compressed ZIP files

### System commands

- [crontab](ebook/en/content/091-the-crontab-command.md) - maintain individual tables used to drive the cron daemon
- [df](ebook/en/content/010-the-df-command.md) - display free disk space
- [du](ebook/en/content/084-the-du-command.md) - display disk usage statistics
- [free](ebook/en/content/018-the-free-command.md) - show memory usage information
- [hostname](ebook/en/content/038-the-hostname-command.md) - set or print name of current host system
- [hostnamectl](ebook/en/content/065-the-hostnamectl-command.md) - change hostname settings
- [ionice](ebook/en/content/083-the-ionice-command.md) - get/set I/O process priority
- [iostat](ebook/en/content/050-the-iostat-command.md) - I/O statistics
- [kill](ebook/en/content/034-the-kill-command.md) - terminate or signal a process by id
- [killall](ebook/en/content/035-the-killall-command.md) - kill processes by name
- [lsblk](ebook/en/content/104-the-lsblk-command.md) - display block and loop devices
- [lsof](ebook/en/content/068-the-lsof-command.md) - list open files
- [mpstat](ebook/en/content/072-the-mpstat-command.md) - CPU statistics
- [ncdu](ebook/en/content/073-the-ncdu-command.md) - curses-based disk usage
- [ps](ebook/en/content/033-the-ps-command.md) - display process status
- [pstree](ebook/en/content/094-the-pstree-command.md) - show processes in tree format
- [reboot](ebook/en/content/058-the-reboot-command.md) - restart the system
- [service](ebook/en/content/070-the-service-command.md) - run an init script
- [shutdown](ebook/en/content/056-the-shutdown-command.md) - close down the system at a specific time
- [top/htop](ebook/en/content/019-the-top-htop-command.md) - display process information
- [uname](ebook/en/content/013-the-uname-command.md) - prints operating system details
- [useradd](ebook/en/content/080-the-useradd-command.md) - add/update user accounts
- [userdel](ebook/en/content/081-the-userdel-command.md) - delete user account
- [usermod](ebook/en/content/082-the-usermod-command.md) - modify user properties
- [vmstat](ebook/en/content/071-the-vmstat-command.md) - virtual memory statistics
- [whereis](ebook/en/content/096-the-whereis-command.md) - locate programs

### Networking Commands

- [dig](ebook/en/content/087-the-dig-command.md) - DNS lookup utility
- [ifconfig](ebook/en/content/041-the-ifconfig-command.md) - configure network interface parameters
- [ip](ebook/en/content/042-the-ip-command.md) - perform network administration tasks
- [iptable](ebook/en/content/066-the-iptable-command.md) - configure IPv4 network firewall
- [lscpu](ebook/en/content/030-the-lscpu-command.md) - display CPU architecture information
- [netstat](ebook/en/content/067-the-netstat-command.md) - show network status
- [ping](ebook/en/content/085-the-ping-command.md) - check network connectivity
- [whois](ebook/en/content/088-the-whois-command.md) - information about Internet domain names and network numbers


### Package Management

- [apt](ebook/en/content/052-the-apt-command.md) - Debian package management
- [rpm](ebook/en/content/075-the-rpm-command.md) - RPM package manager (RedHat)
- [yum](ebook/en/content/053-the-yum-command.md) - package manager for RedHat Linux

### User Information commands
For user modification, see useradd, userdel, usermod under System commands

- [groups](ebook/en/content/023-the-groups-command.md) - show group memberships
- [finger](ebook/en/content/022-the-finger-command.md) - shows information about users
- [last](ebook/en/content/048-the-last-command.md) - displays most recent user logins
- [passwd](ebook/en/content/025-the-passwd-command.md) - modify a user's password
- [w](ebook/en/content/026-the-w-command.md) - display who is logged in and what they are doing
- [who](ebook/en/content/017-the-who-command.md) - display who is logged in
- [whoami](ebook/en/content/027-the-whoami-command.md) - display effective user id

### Session commands

- [clear](ebook/en/content/043-the-clear-command.md) - clear terminal screen
- [env](ebook/en/content/036-the-env-command.md) - display environment variables, or set variables for command execution
- [exit](ebook/en/content/061-the-exit-command.md) - close the active session/shell
- [printenv](ebook/en/content/037-the-printenv-command.md) - print specified environment variables
- [history](ebook/en/content/028-the-history-command.md) - display the command history
- [login](ebook/en/content/029-the-login-command.md) - login and initiate a user session
- [nohup](ebook/en/content/093-the-nohup-command.md) - invoke a utility immune to hangups
- [sleep](ebook/en/content/077-the-sleep-command.md) - suspend execution for a time interval
- [ssh](ebook/en/content/089-the-ssh-command.md) - secure shell login
- [su](ebook/en/content/044-the-su-command.md) - substitute user identity
- [sudo](ebook/en/content/051-the-sudo-command.md) - execute a command as another user
- [screen](ebook/en/content/108-the-screen-command.md) - start a screen session

### Getting Help

- [man](ebook/en/content/024-the-man-command.md) - format and display online manual pages
- [help](ebook/en/content/011-the-help-command.md) - displays help about basic commands not covered by 'man'
- [whatis](ebook/en/content/016-the-whatis-command.md) - display one-line command descriptions

### Applications

- [bc](ebook/en/content/009-the-bc-command.md) - basic calculator
- [cal](ebook/en/content/008-the-cal-command.md) - displays a calendar
- [cmatrix](ebook/en/content/105-the-cmatrix-command.md) - enter the Matrix
- [curl](ebook/en/content/046-the-curl-command.md) - transfer data to or from a server
- [echo](ebook/en/content/021-the-echo-command.md) - display interpreted arguments
- [factor](ebook/en/content/012-the-factor-command.md) - prints prime factors of numbers
- [printf](ebook/en/content/097-the-printf-command.md) - format output
- [sl](ebook/en/content/020-the-sl-command.md) - runs a steam locomotive across your terminal
- [wget](ebook/en/content/045-the-wget-command.md) - non-interactive web file download
- [xargs](ebook/en/content/092-the-xargs-command.md) - construct argument lists and execute utility
- [yes](ebook/en/content/047-the-yes-command.md) - print continous output stream
- [banner](ebook/en/content/112-the-banner-command.md) - Writes ASCII character strings in large letters to standard output.
- [aplay](ebook/en/content/125-the-aplay-command.md) - aplay is a command-line to play audio files.
- [spd-say](ebook/en/content/126-the-spd-say-command.md) - plays the given text as the sound from the command line.
