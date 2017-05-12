
## hdfs dfs -ls /user

* [hdfs@ip-172-31-34-224 /]$ hdfs dfs -ls /user
* Found 8 items
* drwxr-xr-x   - chen   shanghai          0 2017-05-12 03:53 /user/chen
* drwxrwxrwx   - mapred hadoop            0 2017-05-12 03:32 /user/history
* drwxrwxr-t   - hive   hive              0 2017-05-12 03:33 /user/hive
* drwxrwxr-x   - hue    hue               0 2017-05-12 03:34 /user/hue
* drwxrwxr-x   - impala impala            0 2017-05-12 03:34 /user/impala
* drwxrwxr-x   - oozie  oozie             0 2017-05-12 03:34 /user/oozie
* drwxr-x--x   - spark  spark             0 2017-05-12 03:32 /user/spark
* drwxr-xr-x   - zhou   beijin            0 2017-05-12 03:53 /user/zhou
* [hdfs@ip-172-31-34-224 /]$ 

## 2 api/v14/hosts

* hostId	"39c46352-7a02-4ee0-aac2-aadc83a86dd9"
* ipAddress	"172.31.32.94"
* hostname	"ip-172-31-32-94.us-west-2.compute.internal"
* rackId	"/default"
* hostUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/hostRedirect/39c46352-7a02-4ee0-aac2-aadc83a86dd9"
* maintenanceMode	false
* maintenanceOwners	
* commissionState	"COMMISSIONED"
* numCores	4
* numPhysicalCores	4
* totalPhysMemBytes	15740305408
* 1	
* hostId	"f8f7c90b-81fa-427b-a83b-0949c214e00e"
* ipAddress	"172.31.34.224"
* hostname	"ip-172-31-34-224.us-west-2.compute.internal"
* rackId	"/default"
* hostUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/hostRedirect/f8f7c90b-81fa-427b-a83b-0949c214e00e"
* maintenanceMode	false
* maintenanceOwners	
* commissionState	"COMMISSIONED"
* numCores	4
* numPhysicalCores	4
* totalPhysMemBytes	15740305408
* 2	
* hostId	"da96522c-1bdf-4544-827e-a2287d022219"
* ipAddress	"172.31.36.110"
* hostname	"ip-172-31-36-110.us-west-2.compute.internal"
* rackId	"/default"
* hostUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/hostRedirect/da96522c-1bdf-4544-827e-a2287d022219"
* maintenanceMode	false
* maintenanceOwners	
* commissionState	"COMMISSIONED"
* numCores	4
* numPhysicalCores	4
* totalPhysMemBytes	15740305408
* 3	
* hostId	"a8611a46-07fd-4e92-b648-14a30e4bce31"
* ipAddress	"172.31.37.234"
* hostname	"ip-172-31-37-234.us-west-2.compute.internal"
* rackId	"/default"
* hostUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/hostRedirect/a8611a46-07fd-4e92-b648-14a30e4bce31"
* maintenanceMode	false
* maintenanceOwners	
* commissionState	"COMMISSIONED"
* numCores	4
* numPhysicalCores	4
* totalPhysMemBytes	15740305408
* 4	
* hostId	"23a5c6bc-0eb3-47cc-8618-da03fe509e13"
* ipAddress	"172.31.41.98"
* hostname	"ip-172-31-41-98.us-west-2.compute.internal"
* rackId	"/default"
* hostUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/hostRedirect/23a5c6bc-0eb3-47cc-8618-da03fe509e13"
* maintenanceMode	false
* maintenanceOwners	
* commissionState	"COMMISSIONED"
* numCores	4
* numPhysicalCores	4
* totalPhysMemBytes	15740305408

# 3 v6/clusters/Justinzhuo/services


* items	
* 0	
* name	"oozie"
* type	"OOZIE"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/oozie"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"OOZIE_OOZIE_SERVERS_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Oozie"
* 1	
* name	"ks_indexer"
* type	"KS_INDEXER"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/ks_indexer"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"KS_INDEXER_HBASE_INDEXERS_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Key-Value Store Indexer"
* 2	
* name	"spark_on_yarn"
* type	"SPARK_ON_YARN"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/spark_on_yarn"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Spark"
* 3	
* name	"hdfs"
* type	"HDFS"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/hdfs"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"HDFS_BLOCKS_WITH_CORRUPT_REPLICAS"
* summary	"GOOD"
* 1	
* name	"HDFS_CANARY_HEALTH"
* summary	"GOOD"
* 2	
* name	"HDFS_DATA_NODES_HEALTHY"
* summary	"GOOD"
* 3	
* name	"HDFS_FREE_SPACE_REMAINING"
* summary	"GOOD"
* 4	
* name	"HDFS_HA_NAMENODE_HEALTH"
* summary	"GOOD"
* 5	
* name	"HDFS_MISSING_BLOCKS"
* summary	"GOOD"
* 6	
* name	"HDFS_UNDER_REPLICATED_BLOCKS"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"HDFS"
* 4	
* name	"hive"
* type	"HIVE"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/hive"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"HIVE_HIVEMETASTORES_HEALTHY"
* summary	"GOOD"
* 1	
* name	"HIVE_HIVESERVER2S_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Hive"
* 5	
* name	"hbase"
* type	"HBASE"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/hbase"
* serviceState	"STARTED"
* healthSummary	"BAD"
* healthChecks	
* 0	
* name	"HBASE_MASTER_HEALTH"
* summary	"BAD"
* 1	
* name	"HBASE_REGION_SERVERS_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"HBase"
* 6	
* name	"zookeeper"
* type	"ZOOKEEPER"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/zookeeper"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"ZOOKEEPER_CANARY_HEALTH"
* summary	"GOOD"
* 1	
* name	"ZOOKEEPER_SERVERS_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"ZooKeeper"
* 7	
* name	"hue"
* type	"HUE"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/hue"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"HUE_HUE_SERVERS_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Hue"
* 8	
* name	"solr"
* type	"SOLR"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/solr"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"SOLR_SOLR_SERVERS_HEALTHY"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Solr"
* 9	
* name	"impala"
* type	"IMPALA"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/impala"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"IMPALA_ASSIGNMENT_LOCALITY"
* summary	"DISABLED"
* 1	
* name	"IMPALA_CATALOGSERVER_HEALTH"
* summary	"GOOD"
* 2	
* name	"IMPALA_IMPALADS_HEALTHY"
* summary	"GOOD"
* 3	
* name	"IMPALA_STATESTORE_HEALTH"
* summary	"GOOD"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"Impala"
* 10	
* name	"yarn"
* type	"YARN"
* clusterRef	
* clusterName	"cluster"
* serviceUrl	"http://ip-172-31-34-224.us-west-2.compute.internal:7180/cmf/serviceRedirect/yarn"
* serviceState	"STARTED"
* healthSummary	"GOOD"
* healthChecks	
* 0	
* name	"YARN_JOBHISTORY_HEALTH"
* summary	"GOOD"
* 1	
* name	"YARN_NODE_MANAGERS_HEALTHY"
* summary	"GOOD"
* 2	
* name	"YARN_RESOURCEMANAGERS_HEALTH"
* summary	"GOOD"
* 3	
* name	"YARN_USAGE_AGGREGATION_HEALTH"
* summary	"DISABLED"
* configStalenessStatus	"FRESH"
* clientConfigStalenessStatus	"FRESH"
* maintenanceMode	false
* maintenanceOwners	
* displayName	"YARN (MR2 Included)"

