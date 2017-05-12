## 1 ls /etc/yum.repos.d

* [root@ip-172-31-34-224 softwares]# ls /etc/yum.repos.d
* CentOS-Base.repo       CentOS-Vault.repo          cloudera-manager.repo.~2~
* CentOS-Debuginfo.repo  cloudera-manager.repo
* CentOS-Media.repo      cloudera-manager.repo.~1~
* [root@ip-172-31-34-224 softwares]# 


## 2 scm_prepare_database.sh script to create the db.properties
/usr/share/cmf/schema/scm_prepare_database.sh  --host 172.31.36.110 --port 3306  mysql scm scm

## 3

*

## 4

*

## 4 The contents of the db.properties file
* [root@ip-172-31-34-224 cloudera-scm-server]# ls
* db.properties  log4j.properties
* [root@ip-172-31-34-224 cloudera-scm-server]# cat db.properties 
* # Copyright (c) 2012 Cloudera, Inc. All rights reserved.
* #
* # This file describes the database connection.
* #
* 
* # The database type
* # Currently 'mysql', 'postgresql' and 'oracle' are valid databases.
* com.cloudera.cmf.db.type=mysql
* 
* # The database host
* # If a non standard port is needed, use 'hostname:port'
* com.cloudera.cmf.db.host=172.31.36.110
* 
* # The database name
* com.cloudera.cmf.db.name=scm
* 
* # The database user
* com.cloudera.cmf.db.user=scm
* 
* # The database user's password
* com.cloudera.cmf.db.password=Scm@1234
* 
* # The db setup type
* # By default, it is set to INIT
* # If scm-server uses Embedded DB then it is set to EMBEDDED
* # If scm-server uses External DB then it is set to EXTERNAL
* #com.cloudera.cmf.db.setupType=INIT
* com.cloudera.cmf.db.setupType=EXTERNAL
* [root@ip-172-31-34-224 cloudera-scm-server]# 





