## 1 cloud provider：AWS
* 
## 2 nodes ip address and name
* 
* ip-172-31-41-98   ec2-52-42-111-17.us-west-2.compute.amazonaws.com   52.42.111.17   172.31.41.98
* ip-172-31-32-94   ec2-35-165-223-61.us-west-2.compute.amazonaws.com  35.165.223.61  172.31.32.94
* ip-172-31-37-234  ec2-34-208-120-55.us-west-2.compute.amazonaws.com  34.208.120.55  172.31.37.234
* ip-172-31-34-224  ec2-52-88-193-138.us-west-2.compute.amazonaws.com  52.88.193.138  172.31.34.224
* ip-172-31-36-110 ec2-52-24-158-58.us-west-2.compute.amazonaws.com   52.24.158.58   172.31.36.110
* 
## 3 file system capacity for the first node
* 
* [root@ip-172-31-36-110 ~]# df -h
* Filesystem      Size  Used Avail Use% Mounted on
* /dev/xvde        30G  680M   28G   3% /
* tmpfs           7.4G     0  7.4G   0% /dev/shm
* [root@ip-172-31-36-110 ~]# 
## 4 yum repolist enabled
* 
* [root@ip-172-31-36-110 ~]# yum repolist enabled 
* Loaded plugins: fastestmirror, presto
* base                                                     | 3.7 kB     00:00     
* base/primary_db                                          | 4.7 MB     00:02     
* extras                                                   | 3.4 kB     00:00     
* extras/primary_db                                        |  37 kB     00:00     
* updates                                                  | 3.4 kB     00:00     
* updates/primary_db                                       | 821 kB     00:01     
* repo id                        repo name                                  status
* base                           CentOS-6 - Base                            6,706
* extras                         CentOS-6 - Extras                             64
* updates                        CentOS-6 - Updates                           270
* repolist: 7,040
* [root@ip-172-31-36-110 ~]# 
*
* [root@ip-172-31-34-224 ~]# yum repolist enabled
* Loaded plugins: fastestmirror, presto
* base                                                                                        | 3.7 kB     00:00     
* base/primary_db                                                                             | 4.7 MB     00:01     
* extras                                                                                      | 3.4 kB     00:00     
* extras/primary_db                                                                           |  37 kB     00:00     
* updates                                                                                     | 3.4 kB     00:00     
* updates/primary_db                                                                          | 821 kB     00:00     
* repo id                                          repo name                                                   status
* base                                             CentOS-6 - Base                                             6,706
* extras                                           CentOS-6 - Extras                                              64
* updates                                          CentOS-6 - Updates                                            270
* repolist: 7,040
* [root@ip-172-31-34-224 ~]# 
* 
* [root@ip-172-31-37-234 ~]# yum repolist enabled
* Loaded plugins: fastestmirror, presto
* base                                                                                        | 3.7 kB     00:00     
* base/primary_db                                                                             | 4.7 MB     00:02     
* extras                                                                                      | 3.4 kB     00:00     
* extras/primary_db                                                                           |  37 kB     00:00     
* updates                                                                                     | 3.4 kB     00:00     
* updates/primary_db                                                                          | 821 kB     00:00     
* repo id                                          repo name                                                   status
* base                                             CentOS-6 - Base                                             6,706
* extras                                           CentOS-6 - Extras                                              64
* updates                                          CentOS-6 - Updates                                            270
* repolist: 7,040
* [root@ip-172-31-37-234 ~]# 
* 
* [root@ip-172-31-41-98 ~]# yum repolist enabled
* Loaded plugins: fastestmirror, presto
* base                                                                                        | 3.7 kB     00:00     
* base/primary_db                                                                             | 4.7 MB     00:01     
* extras                                                                                      | 3.4 kB     00:00     
* extras/primary_db                                                                           |  37 kB     00:00     
* updates                                                                                     | 3.4 kB     00:00     
* updates/primary_db                                                                          | 821 kB     00:01     
* repo id                                          repo name                                                   status
* base                                             CentOS-6 - Base                                             6,706
* extras                                           CentOS-6 - Extras                                              64
* updates                                          CentOS-6 - Updates                                            270
* repolist: 7,040
* [root@ip-172-31-41-98 ~]# 
* 
* [root@ip-172-31-32-94 ~]# yum repolist enabled
* Loaded plugins: fastestmirror, presto
* base                                                                                        | 3.7 kB     00:00     
* base/primary_db                                                                             | 4.7 MB     00:02     
* extras                                                                                      | 3.4 kB     00:00     
* extras/primary_db                                                                           |  37 kB     00:00     
* updates                                                                                     | 3.4 kB     00:00     
* updates/primary_db                                                                          | 821 kB     00:01     
* repo id                                          repo name                                                   status
* base                                             CentOS-6 - Base                                             6,706
* extras                                           CentOS-6 - Extras                                              64
* updates                                          CentOS-6 - Updates                                            270
* repolist: 7,040
* [root@ip-172-31-32-94 ~]# 
## 5 /etc/passwd entries for zhou and chen & /etc/group
 * groupadd  shanghai  
* groupadd  beijing  
* useradd -u 2900 -G beijing  zhou   
* useradd -u 2300 -G shanghai  chen
* passwd zhou  
* passwd chen  
* cat /etc/passwd
* zhou:x:2900:2900::/home/zhou:/bin/bash
* chen:x:2300:2300::/home/chen:/bin/bash
* 
* cat /etc/group
* shanghai:x:500:chen
* beijing:x:501:zhou
* zhou:x:2900:
* chen:x:2300:

## 6 Cloudera Manager on the second node listed 
*  ip-172-31-34-224  ec2-52-88-193-138.us-west-2.compute.amazonaws.com  52.88.193.138  172.31.34.224
* ps Mysql is * ip-172-31-36-110 ec2-52-24-158-58.us-west-2.compute.amazonaws.com   52.24.158.58   172.31.36.110
