# Basic-Linux-Cheat-Sheet

File & Navigations 

| Command  | Purpose |
| :--- | :--- |
| ls   | directory listing (file/folders on current dir) |
| ls  -l | formatting listing |
| ls -la  | formatted listing using hidden files |
| cd dir   | change dir to dir (dir - directory name) |
| cd .. | change parent directory |
| cd ../dir | change dir in parent directory |
| cd | change home directory |
| pwd | show current directory |
| mkdir dir | create a directory dir |
| rm file | delete file |
| rm -f dir | force remove file |
| rm -r dir | delete directory dir |
| rm -rf dir | remove directory dir |
| rm -rf/ | launch nuclear bombs targeting system  |
| cp file1 file2 | copy file1 to file 2  |
| mv file1 file2 | move file1 to file 2  |
| mv file1 dir/file2 | move file1 to dir as file 2  |
| touch file | create/update file |
| cat file | output contents of file |
| cat > file | write standard input to the file |
| cat >> file | append standard input into file |
| tail -f file | output contents of file as it grows |


 System Info
| Command  | Purpose |
| :------------- | :------------- |
| date | show current date/time |
| uptime | show uptime |
| whoami | who you are logged in as |
| w | display who is online |
| cat/proc/cpuinfo | cpu info |
| cat/proc/meminfo | memory info |
| free | show memory and swap usage |
| du | show directory space usage |
| du -sh | display readable size in GB |
| df | show disk usage |
| uname-a | show kernel config |


Process
| Command  | Purpose |
| :------------- | :------------- |
| ps | display currently active process |
| ps aux | detailed outputs |
| kill pid | kill process with process id |
| kill all proc | kill all processes named proc |


Networking
| Command  | Purpose |
| :------------- | :------------- |
| ping host | ping host |
| whois domain | get whois for domain |
| dig domain  | get DNS for domain |
| dig -x host | reserve lookup host |
| wget file | download file |
| wget -c file | continue stopped download file |
| wget -r url | recursively download files from the url |
| curl url | outputs the webpage from url |
| curl -o meh.html url | writes to the page meh.html |
| ssh user@host | connect host to the user |
| ssh -p port user@host | connectusing port |
| ssh -D user@port | connect & use bind port |

Permissions
| Command  | Purpose |
| :------------- | :------------- |
| chmod octal file | change permissions of file |
| 4 | read (r) |
| 2 | write (w) |
| 1 | execute (x) |
| order | owner/group/world |
| chmod 777 | rwx for everyone |
| chmod 755 | rw for owner, rx for group world |

Compressing
| Command  | Purpose |
| :------------- | :------------- |
| tar cf file.tar files | tar files into file.tar |
| tar xf file.tar | untar into current directory |
| tar tf file.tar | show contents of archive |
| options: |  |
| c | create archive |
| t | table of contents |
| x | extract |
| z | use zip/Gzip |
| f | specify filename |
| j | bzip2 compression |
| w | ask for confirmation |
| k | do not overwrite |
| T | files from file |
| V | verbose |


Others
| Command  | Purpose |
| :------------- | :------------- |
| grep pattern files | search in files for pattern |
| grep -r pattern dir | search for pattern recursively in dir |
| locate file | find all intances of a file |
| whereis app | Find the possible locations of an app |
| man command | show mannual page for command |


Linux File systems
| Command  | Purpose |
| :------------- | :------------- |
| /bin | User binaries |
| /sbin | System binaries |
| /etc | Configuration files |
| /dev | Device files |
| /proc | Process information |
| /var | Variable files |
| /tmp | Temporary files |
| /usr | User programs |
| /home | Home Directories |
| /boot | Boot Loader files |
| /lib | System libraries |
| /opt | Optional add-on apps |
| /mnt | Mount Directory |
| /media | Removable devices |
| /srv | Service Data |
