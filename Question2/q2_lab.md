kartikmoond@MacBookAir ~ % cd ~
mkdir documents
ls -l
mkdir: documents: File exists
total 96
-rwxr-xr-x@   1 kartikmoond  staff  33432 Apr  2  2025 a.out
-rw-r--r--@   1 kartikmoond  staff      0 Mar 31  2025 c
drwxr-xr-x@   7 kartikmoond  staff    224 Apr 14  2025 c language
drwxr-xr-x    9 kartikmoond  staff    288 Dec 22  2023 Cisco Packet Tracer 8.2.1
drwx------@  35 kartikmoond  staff   1120 Dec 28 08:53 Desktop
drwx------+  15 kartikmoond  staff    480 Aug 26 20:07 Documents
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
-rw-r--r--    1 kartikmoond  staff    776 May 16  2024 styles.css
exp: I created a folder named  documents  inside my home directory using  mkdir . The  ls -l  output shows the new directory exists under .

q.2.2
cd ~/documents
touch plan.txt
ls -l
total 0
drwxr-xr-x   7 kartikmoond  staff  224 Apr 26  2025 BITS
drwxr-xr-x   7 kartikmoond  staff  224 Feb 24  2025 Condor Security
drwx------  13 kartikmoond  staff  416 Apr  4  2025 Desktop
drwxr-xr-x   5 kartikmoond  staff  160 Jul 27  2024 Electrician
drwxr-xr-x   9 kartikmoond  staff  288 Apr 16  2025 Job resumes
drwxr-xr-x   2 kartikmoond  staff   64 Feb 24  2025 LOGIXX
-rw-r--r--   1 kartikmoond  staff    0 Dec 28 09:01 plan.txt
drwxr-xr-x@  4 kartikmoond  staff  128 Sep 28  2024 PYTHON
drwxr-xr-x   8 kartikmoond  staff  256 May 17  2025 Resume
drwxr-xr-x   6 kartikmoond  staff  192 May 11  2025 Telus
drwxr-xr-x   9 kartikmoond  staff  288 Feb 25  2025 untitled folder
drwxr-xr-x  10 kartikmoond  staff  320 Feb 24  2025 Work_permit
exp: I navigated into  ~/documents  and created an empty file named  plan.txt  using  touch . The listing confirms  plan.txt  is present in the directory.

q.2.3
echo "This is my project note for the lab." > plan.txt
cat plan.txt
This is my project note for the lab.

q.2.4
ls -l plan.txt
-rw-r--r--  1 kartikmoond  staff  37 Dec 28 09:02 plan.txt

q.2.5
cp plan.txt plan_copy.txt
ls -l
total 16
drwxr-xr-x   7 kartikmoond  staff  224 Apr 26  2025 BITS
drwxr-xr-x   7 kartikmoond  staff  224 Feb 24  2025 Condor Security
drwx------  13 kartikmoond  staff  416 Apr  4  2025 Desktop
drwxr-xr-x   5 kartikmoond  staff  160 Jul 27  2024 Electrician
drwxr-xr-x   9 kartikmoond  staff  288 Apr 16  2025 Job resumes
drwxr-xr-x   2 kartikmoond  staff   64 Feb 24  2025 LOGIXX
-rw-r--r--   1 kartikmoond  staff   37 Dec 28 09:04 plan_copy.txt
-rw-r--r--   1 kartikmoond  staff   37 Dec 28 09:02 plan.txt
drwxr-xr-x@  4 kartikmoond  staff  128 Sep 28  2024 PYTHON
drwxr-xr-x   8 kartikmoond  staff  256 May 17  2025 Resume
drwxr-xr-x   6 kartikmoond  staff  192 May 11  2025 Telus
drwxr-xr-x   9 kartikmoond  staff  288 Feb 25  2025 untitled folder
drwxr-xr-x  10 kartikmoond  staff  320 Feb 24  2025 Work_permit

q.2.6
cd ~
mv documents project_documents
ls -l
mv: rename documents to project_documents: Permission denied
total 96
-rwxr-xr-x@   1 kartikmoond  staff  33432 Apr  2  2025 a.out
-rw-r--r--@   1 kartikmoond  staff      0 Mar 31  2025 c
drwxr-xr-x@   7 kartikmoond  staff    224 Apr 14  2025 c language
drwxr-xr-x    9 kartikmoond  staff    288 Dec 22  2023 Cisco Packet Tracer 8.2.1
drwx------@  38 kartikmoond  staff   1216 Dec 28 09:04 Desktop
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
-rw-r--r--    1 kartikmoond  staff    776 May 16  2024 styles.css


q.2.7
mkdir ~/project_documents/archive
ls -l ~/project_documents
mkdir: /Users/kartikmoond/project_documents: No such file or directory
ls: /Users/kartikmoond/project_documents: No such file or directory

q.2.8
 mv ~/project_documents/plan_copy.txt ~/project_documents/archive/
ls -l ~/project_documents/archive
mv: rename /Users/kartikmoond/project_documents/plan_copy.txt to /Users/kartikmoond/project_documents/archive/: No such file or directory
ls: /Users/kartikmoond/project_documents/archive: No such file or directory

q.2.9
ls -R ~/project_documents
ls: /Users/kartikmoond/project_documents: No such file or directory

q.2.10
 readlink -f ~/project_documents/archive/plan_copy.txt

