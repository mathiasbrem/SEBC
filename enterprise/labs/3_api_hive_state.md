curl -X POST -u mathiasbrem:cloudera 'http://54.186.76.200:7180/api/v1/clusters/Cluster%201/services/hive/commands/start'

curl -X POST -u mathiasbrem:cloudera 'http://54.186.76.200:7180/api/v1/clusters/Cluster%201/services/hive/commands/stop'

curl  -u mathiasbrem:cloudera 'http://localhost:7180/api/v1/clusters/Cluster%201/services/hive'



[root@ed ~]# curl -X POST -u mathiasbrem:cloudera 'http://54.186.76.200:7180/api/v1/clusters/Cluster%201/services/hive/commands/start'
{
  "id" : 1213,
  "name" : "Start",
  "startTime" : "2017-04-05T14:53:39.429Z",
  "endTime" : "2017-04-05T14:53:39.429Z",
  "active" : false,
  "success" : false,
  "resultMessage" : "Command Start is not currently available for execution.",
  "serviceRef" : {
    "clusterName" : "cluster",
    "serviceName" : "hive"
  }
}

[root@ed ~]# curl -X POST -u mathiasbrem:cloudera 'http://54.186.76.200:7180/api/v1/clusters/Cluster%201/services/hive/commands/stop'
{
  "id" : 1214,
  "name" : "Stop",
  "startTime" : "2017-04-05T14:53:39.479Z",
  "active" : true,
  "serviceRef" : {
    "clusterName" : "cluster",
    "serviceName" : "hive"
  }
}

[root@ed ~]# curl  -u mathiasbrem:cloudera 'http://localhost:7180/api/v1/clusters/Cluster%201/services/hive'
{
  "name" : "hive",
  "type" : "HIVE",
  "clusterRef" : {
    "clusterName" : "cluster"
  },
  "serviceUrl" : "http://ed:7180/cmf/serviceRedirect/hive",
  "serviceState" : "STOPPED",
  "healthSummary" : "GOOD",
  "healthChecks" : [ {
    "name" : "HIVE_HIVEMETASTORES_HEALTHY",
    "summary" : "GOOD"
  }, {
    "name" : "HIVE_HIVESERVER2S_HEALTHY",
    "summary" : "GOOD"
  } ],
  "configStale" : false
}
