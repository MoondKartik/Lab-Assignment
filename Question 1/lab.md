q1.1

whoami
id
kartikmoond
uid=501(kartikmoond) gid=20(staff) groups=20(staff),12(everyone),61(localaccounts),79(_appserverusr),80(admin),81(_appserveradm),98(_lpadmin),101(access_bpf),701(com.apple.sharepoint.group.1),702(com.apple.sharepoint.group.2),33(_appstore),100(_lpoperator),204(_developer),250(_analyticsusers),395(com.apple.access_ftp),398(com.apple.access_screensharing),399(com.apple.access_ssh),400(com.apple.access_remote_ae)

1.2
pwd
ls -l
/Users/kartikmoond
total 120
-rwxr-xr-x@   1 kartikmoond  staff  33432 Apr  2  2025 a.out
-rw-r--r--@   1 kartikmoond  staff      0 Mar 31  2025 c
drwxr-xr-x@   7 kartikmoond  staff    224 Apr 14  2025 c language
drwxr-xr-x    9 kartikmoond  staff    288 Dec 22  2023 Cisco Packet Tracer 8.2.1
drwx------@  45 kartikmoond  staff   1440 Dec 28 09:48 Desktop
drwx------+  17 kartikmoond  staff    544 Dec 28 09:04 Documents
drwx------@ 176 kartikmoond  staff   5632 Dec 24 22:52 Downloads
-rw-r--r--@   1 kartikmoond  staff     75 Apr  2  2025 hello.c
-rw-r--r--@   1 kartikmoond  staff    162 Nov  7  2024 hello.py
drwxr-xr-x    5 kartikmoond  staff    160 May 16  2024 jai
drwxr-xr-x    6 kartikmoond  staff    192 Dec 24 22:26 Lab-Assignment
drwx------@ 103 kartikmoond  staff   3296 Sep 16 21:41 Library
drwx------    5 kartikmoond  staff    160 May 10  2024 Movies
drwx------+   4 kartikmoond  staff    128 Oct 19  2023 Music
drwx------+   4 kartikmoond  staff    128 Oct  7  2023 Pictures
drwxr-xr-x+   4 kartikmoond  staff    128 Oct  7  2023 Public
drwxr-xr-x@   3 kartikmoond  staff     96 Apr 26  2024 PycharmProjects
-rw-r--r--    2 kartikmoond  staff     31 Dec 28 09:25 sample_data.txt
-rw-r--r--    2 kartikmoond  staff     31 Dec 28 09:25 sample_hard.txt
-rw-r--r--    1 kartikmoond  staff    776 May 16  2024 styles.css
-rw-r--r--    1 kartikmoond  staff    136 Dec 28 09:43 system_report.txt

1.3

echo "Linux user environment verified" > user_info.txt
cat user_info.txt
Linux user environment verified

1.4
wc -c user_info.txt
      32 user_info.txt

1.5
MKDIR(1)                                                                      General Commands Manual                                                                      MKDIR(1)

NAME
     mkdir – make directories

SYNOPSIS
     mkdir [-pv] [-m mode] directory_name ...

DESCRIPTION
     The mkdir utility creates the directories named as operands, in the order specified, using mode “rwxrwxrwx” (0777) as modified by the current umask(2).

     The options are as follows:

     -m mode        Set the file permission bits of the final created directory to the specified mode.  The mode argument can be in any of the formats specified to the chmod(1)
                    command.  If a symbolic mode is specified, the operation characters ‘+’ and ‘-’ are interpreted relative to an initial mode of “a=rwx”.

     -p             Create intermediate directories as required.  If this option is not specified, the full path prefix of each operand must already exist.  On the other hand,
                    with this option specified, no error will be reported if a directory given as an operand already exists.  Intermediate directories are created with permission
                    bits of “rwxrwxrwx” (0777) as modified by the current umask, plus write and search permission for the owner.

     -v             Be verbose when creating directories, listing them as they are created.

     The user must have write permission in the parent directory.

EXIT STATUS
     The mkdir utility exits 0 on success, and >0 if an error occurs.

EXAMPLES
     Create a directory named foobar:

           $ mkdir foobar

     Create a directory named foobar and set its file mode to 700:

           $ mkdir -m 700 foobar

     Create a directory named cow/horse/monkey, creating any non-existent intermediate directories as necessary:

           $ mkdir -p cow/horse/monkey

COMPATIBILITY
     The -v option is non-standard and its use in scripts is not recommended.

SEE ALSO
     rmdir(1)

STANDARDS
     The mkdir utility is expected to be IEEE Std 1003.2 (“POSIX.2”) compatible.

HISTORY
     A mkdir command appeared in Version 1 AT&T UNIX.

macOS 15.6                                                          

1.6
cd ~
ls -al | sort
-rw-------    1 kartikmoond  staff     20 Dec 28 09:50 .lesshst
-rw-------    1 kartikmoond  staff  25865 Dec 28 09:47 .zsh_history
-rw-------@   1 kartikmoond  staff     16 Oct 10  2023 .emulator_console_auth_token
-rw-r--r--    1 kartikmoond  staff     32 Dec 28 09:48 user_info.txt
-rw-r--r--    1 kartikmoond  staff     43 Oct  7  2023 .zprofile.pysave
-rw-r--r--    1 kartikmoond  staff     64 Oct  7  2023 .gitconfig
-rw-r--r--    1 kartikmoond  staff    118 Oct  7  2023 .bashrc
-rw-r--r--    1 kartikmoond  staff    118 Oct  7  2023 .mkshrc
-rw-r--r--    1 kartikmoond  staff    118 Oct  7  2023 .zlogin
-rw-r--r--    1 kartikmoond  staff    136 Dec 28 09:43 system_report.txt
-rw-r--r--    1 kartikmoond  staff    200 Oct  7  2023 .bash_profile
-rw-r--r--    1 kartikmoond  staff    236 Oct  7  2023 .profile
-rw-r--r--    1 kartikmoond  staff    256 Jan  2  2024 .packettracer
-rw-r--r--    1 kartikmoond  staff    279 Oct  8  2023 .zshrc
-rw-r--r--    1 kartikmoond  staff    293 Jan 20  2025 .zprofile
-rw-r--r--    1 kartikmoond  staff    776 May 16  2024 styles.css
-rw-r--r--    2 kartikmoond  staff     31 Dec 28 09:25 sample_data.txt
-rw-r--r--    2 kartikmoond  staff     31 Dec 28 09:25 sample_hard.txt
-rw-r--r--@   1 kartikmoond  staff      0 Mar 31  2025 c
-rw-r--r--@   1 kartikmoond  staff     75 Apr  2  2025 hello.c
-rw-r--r--@   1 kartikmoond  staff    162 Nov  7  2024 hello.py
-rw-r--r--@   1 kartikmoond  staff  18436 Dec 24 23:02 .DS_Store
-rwxr-xr-x@   1 kartikmoond  staff  33432 Apr  2  2025 a.out
drwx------    5 kartikmoond  staff    160 May 10  2024 Movies
drwx------   15 kartikmoond  staff    480 Dec 28 09:47 .zsh_sessions
drwx------@   4 kartikmoond  staff    128 Jan 11  2024 .config
drwx------@  48 kartikmoond  staff   1536 Dec 28 09:49 Desktop
drwx------@ 103 kartikmoond  staff   3296 Sep 16 21:41 Library
drwx------@ 176 kartikmoond  staff   5632 Dec 24 22:52 Downloads
drwx------+   4 kartikmoond  staff    128 Oct  7  2023 Pictures
drwx------+   4 kartikmoond  staff    128 Oct 19  2023 Music
drwx------+  17 kartikmoond  staff    544 Dec 28 09:04 Documents
drwx------+  61 kartikmoond  staff   1952 Dec 28 09:45 .Trash
drwxr-x---+  58 kartikmoond  staff   1856 Dec 28 09:50 .
drwxr-xr-x    3 kartikmoond  staff     96 Oct  7  2023 .cache
drwxr-xr-x    3 kartikmoond  staff     96 Oct 11  2023 .hawtjni
drwxr-xr-x    4 kartikmoond  staff    128 May  1  2025 .omnissa
drwxr-xr-x    4 kartikmoond  staff    128 Oct  8  2023 .bundle
drwxr-xr-x    4 kartikmoond  staff    128 Oct  8  2023 .cocoapods
drwxr-xr-x    4 kartikmoond  staff    128 Oct  8  2023 .gem
drwxr-xr-x    4 kartikmoond  staff    128 Oct 10  2023 .local
drwxr-xr-x    5 kartikmoond  staff    160 May 16  2024 jai
drwxr-xr-x    5 kartikmoond  staff    160 Oct  8  2023 .rbenv
drwxr-xr-x    5 kartikmoond  staff    160 Oct 27  2023 .swiftpm
drwxr-xr-x    6 kartikmoond  staff    192 Dec 24 22:26 Lab-Assignment
drwxr-xr-x    6 kartikmoond  staff    192 Oct  7  2023 .npm
drwxr-xr-x    7 root         admin    224 Aug 28 04:16 ..
drwxr-xr-x    8 kartikmoond  staff    256 Oct 20  2023 .expo
drwxr-xr-x    9 kartikmoond  staff    288 Dec 22  2023 Cisco Packet Tracer 8.2.1
drwxr-xr-x   12 kartikmoond  staff    384 Oct 10  2023 .gradle
drwxr-xr-x   31 kartikmoond  staff    992 Oct 16  2023 .rvm
drwxr-xr-x@   3 kartikmoond  staff     96 Apr 26  2024 PycharmProjects
drwxr-xr-x@   3 kartikmoond  staff     96 Oct 19  2023 .vscode-react-native
drwxr-xr-x@   5 kartikmoond  staff    160 Oct 10  2023 .vscode
drwxr-xr-x@   7 kartikmoond  staff    224 Apr 14  2025 c language
drwxr-xr-x@  11 kartikmoond  staff    352 Oct 27  2023 .android
drwxr-xr-x@  15 kartikmoond  staff    480 Dec 28 08:55 .anydesk
drwxr-xr-x+   4 kartikmoond  staff    128 Oct  7  2023 Public
total 320

1.7

grep admin log.txt
grep: log.txt: No such file or directory

1.8

 uname -r
24.6.0


1.9

ping -c 4 www.google.com
PING www.google.com (192.178.192.106): 56 data bytes
64 bytes from 192.178.192.106: icmp_seq=0 ttl=110 time=15.727 ms
64 bytes from 192.178.192.106: icmp_seq=1 ttl=110 time=24.474 ms
64 bytes from 192.178.192.106: icmp_seq=2 ttl=110 time=24.073 ms
64 bytes from 192.178.192.106: icmp_seq=3 ttl=110 time=20.928 ms

--- www.google.com ping statistics ---
4 packets transmitted, 4 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 15.727/21.300/24.474/3.499 ms


1.10

uptime
 9:52  up 31 days, 13:03, 3 users, load averages: 2.36 1.95 1.82
