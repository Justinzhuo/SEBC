## 1 ls /etc/yum.repos.d

* [root@ip-172-31-34-224 softwares]# ls /etc/yum.repos.d
* CentOS-Base.repo       CentOS-Vault.repo          cloudera-manager.repo.~2~
* CentOS-Debuginfo.repo  cloudera-manager.repo
* CentOS-Media.repo      cloudera-manager.repo.~1~
* [root@ip-172-31-34-224 softwares]# 


## 2 scm_prepare_database.sh script to create the db.properties
/usr/share/cmf/schema/scm_prepare_database.sh  --host 172.31.36.110 --port 3306  mysql scm scm

