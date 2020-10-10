# YUM-repo-file

This repository contains the REPOSITORY file required to configure YUM in your RHEL8 / CentOS Linux Operating systems. 

# Steps to do configuration :-
1. First, login as ROOT user in your RHEL8 / CentOS Linux System
2. Open the Command Line Terminal in your system
3. Create a directory in your system using the following command:-

*mkdir /root/cloning*

4. After that confirm the creation of the directory using the command:

*ls | grep cloning*

5. Now, go inside the created directory using the following command:

*cd /root/cloning/*

6. When landed inside the folder, just clone the code using the command:

*git clone https://github.com/Prayag15-bit/YUM-repo-file.git*

7. After cloning is done, move the file to the YUM repositories folder using:

*mv /root/cloning/rhel8.repo /etc/yum.repos.d/ -f*

8. Remove the cloning folder by:

*rm /root/cloning/ -rvf*

# BOOM!! Your YUM is configured successfully. Check for the output using: *yum repolist*
