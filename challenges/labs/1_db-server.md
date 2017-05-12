## 1 database server
* ip-172-31-36-110 ec2-52-24-158-58.us-west-2.compute.amazonaws.com   52.24.158.58   172.31.36.110
## 2  database server version


* mysql> status;
* --------------
* mysql  Ver 14.14 Distrib 5.7.18, for Linux (x86_64) using  EditLine wrapper
* 
* Connection id:          359
* Current database:
* Current user:           root@localhost
* SSL:                    Not in use
* Current pager:          stdout
* Using outfile:          ''
* Using delimiter:        ;
* Server version:         5.7.18 MySQL Community Server (GPL)
* Protocol version:       10
* Connection:             Localhost via UNIX socket
* Server characterset:    latin1
* Db     characterset:    latin1
* Client characterset:    utf8
* Conn.  characterset:    utf8
* UNIX socket:            /var/lib/mysql/mysql.sock
* Uptime:                 29 min 18 sec
* 
* Threads: 6  Questions: 76385  Slow queries: 0  Opens: 832  Flush tables: 1  Open tables: 219  Queries per second avg: 43.449
* --------------

## 3 listing the databases created 
* mysql> show databases;
* +--------------------+
* | Database           |
* +--------------------+
* | information_schema |
* | hive               |
* | hue                |
* | mysql              |
* | nav                |
* | oozie              |
* | performance_schema |
* | rman               |
* | scm                |
* | sentry             |
* | sys                |
* +--------------------+
* 11 rows in set (0.00 sec)
