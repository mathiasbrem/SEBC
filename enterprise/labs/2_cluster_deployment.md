{
  "timestamp" : "2017-04-05T14:24:28.700Z",
  "clusters" : [ {
    "name" : "Cluster 1",
    "version" : "CDH5",
    "services" : [ {
      "name" : "zookeeper",
      "type" : "ZOOKEEPER",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "SERVER",
          "items" : [ {
            "name" : "zookeeper_server_java_heapsize",
            "value" : "813694976"
          } ]
        } ],
        "items" : [ ]
      },
      "roles" : [ {
        "name" : "zookeeper-SERVER-52d82d6ecb6f49278fad625cd818315c",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "afecd5c4-e881-414c-a560-d44e2f14575c"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "8zwe7s997y5n15br6etd8misv"
          }, {
            "name" : "serverId",
            "value" : "1"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-81b3f57b5d45161124cff7398fa7fac9",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "85bf31a9-422e-480f-be6e-1a3835bbd098"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "9fyv9l1rgvnpc47d0o7mery46"
          }, {
            "name" : "serverId",
            "value" : "3"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-df3394bbbabb712ed98f181d208a0658",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "112sxerz4t3mpwm8zvk24hm38"
          }, {
            "name" : "serverId",
            "value" : "4"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-dfc0a82817c830054300b645975d497a",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "2dlisfwxoyl2qjhqom1dmex73"
          }, {
            "name" : "serverId",
            "value" : "2"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-f224fa1817cb4eb64c729f8acc7024ef",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "bd6a4bd7-8c96-420d-a793-73064da042fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "83tpirj7ycgfve7emzis77t5j"
          }, {
            "name" : "serverId",
            "value" : "5"
          } ]
        }
      } ],
      "displayName" : "ZooKeeper"
    }, {
      "name" : "oozie",
      "type" : "OOZIE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "OOZIE_SERVER",
          "items" : [ {
            "name" : "oozie_database_host",
            "value" : "ed"
          }, {
            "name" : "oozie_database_password",
            "value" : "cloudera-scm"
          }, {
            "name" : "oozie_database_type",
            "value" : "mysql"
          }, {
            "name" : "oozie_database_user",
            "value" : "cloudera-scm"
          } ]
        } ],
        "items" : [ {
          "name" : "hive_service",
          "value" : "hive"
        }, {
          "name" : "mapreduce_yarn_service",
          "value" : "yarn"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "oozie-OOZIE_SERVER-df3394bbbabb712ed98f181d208a0658",
        "type" : "OOZIE_SERVER",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "5a89c094yg2v2klmr1dw1floq"
          } ]
        }
      } ],
      "displayName" : "Oozie"
    }, {
      "name" : "hue",
      "type" : "HUE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "HUE_SERVER",
          "items" : [ {
            "name" : "hue_server_bind_wildcard",
            "value" : "true"
          } ]
        } ],
        "items" : [ {
          "name" : "database_host",
          "value" : "ed"
        }, {
          "name" : "database_password",
          "value" : "cloudera-scm"
        }, {
          "name" : "database_type",
          "value" : "mysql"
        }, {
          "name" : "database_user",
          "value" : "cloudera-scm"
        }, {
          "name" : "hive_service",
          "value" : "hive"
        }, {
          "name" : "hue_webhdfs",
          "value" : "hdfs-HTTPFS-dfc0a82817c830054300b645975d497a"
        }, {
          "name" : "oozie_service",
          "value" : "oozie"
        }, {
          "name" : "whitelist",
          "value" : "*"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hue-HUE_SERVER-df3394bbbabb712ed98f181d208a0658",
        "type" : "HUE_SERVER",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "bxofo47k7zdvht68swrsjgzh5"
          }, {
            "name" : "secret_key",
            "value" : "ge0I1r3s9hJxMAoamLEECdMcfPCnvn"
          } ]
        }
      } ],
      "displayName" : "Hue"
    }, {
      "name" : "hdfs",
      "type" : "HDFS",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "DATANODE",
          "items" : [ {
            "name" : "datanode_java_heapsize",
            "value" : "1073741824"
          }, {
            "name" : "dfs_data_dir_list",
            "value" : "/dfs/dn"
          }, {
            "name" : "dfs_datanode_du_reserved",
            "value" : "4293264998"
          }, {
            "name" : "dfs_datanode_max_locked_memory",
            "value" : "4294967296"
          }, {
            "name" : "rm_cpu_shares",
            "value" : "200"
          }, {
            "name" : "rm_io_weight",
            "value" : "100"
          } ]
        }, {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "dfs_client_use_trash",
            "value" : "true"
          } ]
        }, {
          "roleType" : "JOURNALNODE",
          "items" : [ {
            "name" : "dfs_journalnode_edits_dir",
            "value" : "/dfs/jornal"
          } ]
        }, {
          "roleType" : "NAMENODE",
          "items" : [ {
            "name" : "dfs_name_dir_list",
            "value" : "/dfs/nn"
          }, {
            "name" : "dfs_namenode_servicerpc_address",
            "value" : "8022"
          } ]
        }, {
          "roleType" : "SECONDARYNAMENODE",
          "items" : [ {
            "name" : "fs_checkpoint_dir_list",
            "value" : "/dfs/snn"
          } ]
        } ],
        "items" : [ {
          "name" : "dfs_ha_fencing_cloudera_manager_secret_key",
          "value" : "MXPSjkRrC4YQvbVAmLWrA87fbPMJU1"
        }, {
          "name" : "dfs_ha_fencing_methods",
          "value" : "shell(true)"
        }, {
          "name" : "fc_authorization_secret_key",
          "value" : "2rT1q6VcoEo7BTihbhE9xEJWYvKXsL"
        }, {
          "name" : "http_auth_signature_secret",
          "value" : "wjO4OPNG3WdJtpRk5EzuBqrahiYgX1"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "10"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hdfs-DATANODE-52d82d6ecb6f49278fad625cd818315c",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "afecd5c4-e881-414c-a560-d44e2f14575c"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "342hsxi0m3nmkpbzp6yt6dau7"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-81b3f57b5d45161124cff7398fa7fac9",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "85bf31a9-422e-480f-be6e-1a3835bbd098"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "67igcn5fhm5qnhjisq4z44od8"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-f224fa1817cb4eb64c729f8acc7024ef",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "bd6a4bd7-8c96-420d-a793-73064da042fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "8weuqqp4dtycule9ndh3qnlc7"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-df3394bbbabb712ed98f181d208a0658",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "c070284da8y4lubnam00cm13v"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-dfc0a82817c830054300b645975d497a",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "4hp9b0em6ithtt3kgzf2s2gyw"
          } ]
        }
      }, {
        "name" : "hdfs-HTTPFS-dfc0a82817c830054300b645975d497a",
        "type" : "HTTPFS",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "85qqrkdui1x5o2w0tc9rg0y08"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-52d82d6ecb6f49278fad625cd818315c",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "afecd5c4-e881-414c-a560-d44e2f14575c"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "9cuqla6bg5tfzvanfm67z6m6b"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-81b3f57b5d45161124cff7398fa7fac9",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "85bf31a9-422e-480f-be6e-1a3835bbd098"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "a5xudik9bjk60k22zryfirebo"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-df3394bbbabb712ed98f181d208a0658",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "ako99pen0rzcfr0vy3wphu6s0"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-dfc0a82817c830054300b645975d497a",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "e3jbjunpsh9to12uct0gy9utl"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-f224fa1817cb4eb64c729f8acc7024ef",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "bd6a4bd7-8c96-420d-a793-73064da042fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "aj77gkzag4wtkjjf1nzhob8oz"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-df3394bbbabb712ed98f181d208a0658",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover_enabled",
            "value" : "true"
          }, {
            "name" : "dfs_federation_namenode_nameservice",
            "value" : "nameservice1"
          }, {
            "name" : "dfs_namenode_quorum_journal_name",
            "value" : "nameservice1"
          }, {
            "name" : "namenode_id",
            "value" : "62"
          }, {
            "name" : "role_jceks_password",
            "value" : "7hko3r0dozcp42jv03ua3kqir"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-dfc0a82817c830054300b645975d497a",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover_enabled",
            "value" : "true"
          }, {
            "name" : "dfs_federation_namenode_nameservice",
            "value" : "nameservice1"
          }, {
            "name" : "dfs_namenode_quorum_journal_name",
            "value" : "nameservice1"
          }, {
            "name" : "namenode_id",
            "value" : "48"
          }, {
            "name" : "role_jceks_password",
            "value" : "450fhd6flohxdhl1vjhfj2033"
          } ]
        }
      } ],
      "displayName" : "HDFS"
    }, {
      "name" : "yarn",
      "type" : "YARN",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "mapred_reduce_tasks",
            "value" : "6"
          }, {
            "name" : "mapred_submit_replication",
            "value" : "1"
          } ]
        }, {
          "roleType" : "NODEMANAGER",
          "items" : [ {
            "name" : "rm_cpu_shares",
            "value" : "1800"
          }, {
            "name" : "rm_io_weight",
            "value" : "900"
          }, {
            "name" : "yarn_nodemanager_heartbeat_interval_ms",
            "value" : "100"
          }, {
            "name" : "yarn_nodemanager_local_dirs",
            "value" : "/yarn/nm"
          }, {
            "name" : "yarn_nodemanager_log_dirs",
            "value" : "/yarn/container-logs"
          }, {
            "name" : "yarn_nodemanager_resource_cpu_vcores",
            "value" : "3"
          }, {
            "name" : "yarn_nodemanager_resource_memory_mb",
            "value" : "3264"
          } ]
        }, {
          "roleType" : "RESOURCEMANAGER",
          "items" : [ {
            "name" : "yarn_scheduler_maximum_allocation_mb",
            "value" : "3264"
          }, {
            "name" : "yarn_scheduler_maximum_allocation_vcores",
            "value" : "3"
          } ]
        } ],
        "items" : [ {
          "name" : "hdfs_service",
          "value" : "hdfs"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "90"
        }, {
          "name" : "yarn_service_cgroups",
          "value" : "false"
        }, {
          "name" : "yarn_service_lce_always",
          "value" : "false"
        }, {
          "name" : "zk_authorization_secret_key",
          "value" : "geTMaMCFMUsybHLnLjj3o0hbGcVaNv"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "yarn-JOBHISTORY-dfc0a82817c830054300b645975d497a",
        "type" : "JOBHISTORY",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "5nnvywvbwgrov8dfhgo8g5woq"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-52d82d6ecb6f49278fad625cd818315c",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "afecd5c4-e881-414c-a560-d44e2f14575c"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "984dqx2hxjin5lgt6860dmwqq"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-81b3f57b5d45161124cff7398fa7fac9",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "85bf31a9-422e-480f-be6e-1a3835bbd098"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "ed8mxgb9jpjkcqpqt5hfqafeh"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-f224fa1817cb4eb64c729f8acc7024ef",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "bd6a4bd7-8c96-420d-a793-73064da042fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "3lkxawslu9qc4pyrlp6vbxi24"
          } ]
        }
      }, {
        "name" : "yarn-RESOURCEMANAGER-dfc0a82817c830054300b645975d497a",
        "type" : "RESOURCEMANAGER",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "rm_id",
            "value" : "53"
          }, {
            "name" : "role_jceks_password",
            "value" : "2bksls4s89aslm3131fjx89ri"
          } ]
        }
      } ],
      "displayName" : "YARN (MR2 Included)"
    }, {
      "name" : "hive",
      "type" : "HIVE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "HIVEMETASTORE",
          "items" : [ {
            "name" : "hive_metastore_java_heapsize",
            "value" : "813694976"
          } ]
        }, {
          "roleType" : "HIVESERVER2",
          "items" : [ {
            "name" : "hiveserver2_java_heapsize",
            "value" : "3105882112"
          }, {
            "name" : "hiveserver2_spark_driver_memory",
            "value" : "966367641"
          }, {
            "name" : "hiveserver2_spark_executor_cores",
            "value" : "4"
          }, {
            "name" : "hiveserver2_spark_executor_memory",
            "value" : "3432356249"
          }, {
            "name" : "hiveserver2_spark_yarn_driver_memory_overhead",
            "value" : "102"
          }, {
            "name" : "hiveserver2_spark_yarn_executor_memory_overhead",
            "value" : "577"
          } ]
        } ],
        "items" : [ {
          "name" : "hive_metastore_database_host",
          "value" : "ed"
        }, {
          "name" : "hive_metastore_database_password",
          "value" : "cloudera-scm"
        }, {
          "name" : "hive_metastore_database_user",
          "value" : "cloudera-scm"
        }, {
          "name" : "mapreduce_yarn_service",
          "value" : "yarn"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hive-GATEWAY-52d82d6ecb6f49278fad625cd818315c",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "afecd5c4-e881-414c-a560-d44e2f14575c"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-81b3f57b5d45161124cff7398fa7fac9",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "85bf31a9-422e-480f-be6e-1a3835bbd098"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-df3394bbbabb712ed98f181d208a0658",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-dfc0a82817c830054300b645975d497a",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-f224fa1817cb4eb64c729f8acc7024ef",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "bd6a4bd7-8c96-420d-a793-73064da042fe"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-HIVEMETASTORE-df3394bbbabb712ed98f181d208a0658",
        "type" : "HIVEMETASTORE",
        "hostRef" : {
          "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "2py5xnthmku89xoqy1zdl8x2a"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-dfc0a82817c830054300b645975d497a",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "81xk7styl3lin8yxl08t6dkpe"
          } ]
        }
      } ],
      "displayName" : "Hive"
    } ]
  } ],
  "hosts" : [ {
    "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e",
    "ipAddress" : "172.31.100.202",
    "hostname" : "ed",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "host_config_suppression_memory_overcommitted_validator",
        "value" : "true"
      } ]
    }
  }, {
    "hostId" : "cc80eab4-4447-49ed-95ba-9c8576e884b2",
    "ipAddress" : "172.31.100.187",
    "hostname" : "master",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "host_config_suppression_memory_overcommitted_validator",
        "value" : "true"
      } ]
    }
  }, {
    "hostId" : "85bf31a9-422e-480f-be6e-1a3835bbd098",
    "ipAddress" : "172.31.100.241",
    "hostname" : "worker1",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "memory_overcommit_threshold",
        "value" : "0.9"
      } ]
    }
  }, {
    "hostId" : "afecd5c4-e881-414c-a560-d44e2f14575c",
    "ipAddress" : "172.31.100.239",
    "hostname" : "worker2",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "memory_overcommit_threshold",
        "value" : "0.9"
      } ]
    }
  }, {
    "hostId" : "bd6a4bd7-8c96-420d-a793-73064da042fe",
    "ipAddress" : "172.31.100.75",
    "hostname" : "worker3",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "memory_overcommit_threshold",
        "value" : "0.9"
      } ]
    }
  } ],
  "users" : [ {
    "name" : "__cloudera_internal_user__mgmt-ACTIVITYMONITOR-df3394bbbabb712ed98f181d208a0658",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "2b7e8f9f8eff628d3d0ca3915502d2f19bd1fb14486f8b5fbb6432c062eb8a3e",
    "pwSalt" : 133524471249272014,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-EVENTSERVER-df3394bbbabb712ed98f181d208a0658",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "9ad268521cdae82ad881fc0a8662ba06e3d7d777c5de37446bd8184960e476c5",
    "pwSalt" : 1040721329181808069,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-HOSTMONITOR-df3394bbbabb712ed98f181d208a0658",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "0f21141d2d48e7ba0ed775a760dce2fea7523af496e427a724f55e705b1e6dfb",
    "pwSalt" : -3754421848114863588,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-REPORTSMANAGER-df3394bbbabb712ed98f181d208a0658",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "52edfd26ad9276e6a0db307dff835c4f3336a8bf7966e5e8168babe9b26fba9e",
    "pwSalt" : -7401510422979787653,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-SERVICEMONITOR-df3394bbbabb712ed98f181d208a0658",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "2bef308aa9aa6413751d55621caa09b37096dc62c731eac88729023cdea3fc1a",
    "pwSalt" : -3066378602735915921,
    "pwLogin" : true
  }, {
    "name" : "admin",
    "roles" : [ "ROLE_LIMITED" ],
    "pwHash" : "84618541b6f631e99ef839421acfd46b6b0003f55cd966f65818ecdd534a50a5",
    "pwSalt" : 1935482974478514547,
    "pwLogin" : true
  }, {
    "name" : "mathiasbrem",
    "roles" : [ "ROLE_ADMIN" ],
    "pwHash" : "bbb6dbcd2ad22ab5eeb3f5dee47ef94b6006c2b0a94ccba638b8886bf46d7a7e",
    "pwSalt" : -1377944777310451440,
    "pwLogin" : true
  }, {
    "name" : "minotaur",
    "roles" : [ "ROLE_CONFIGURATOR" ],
    "pwHash" : "fdf776e1fad8ff3e11c62c3ab8c7f904af8a90af00a3d0eb835d3df219adac0a",
    "pwSalt" : 104386500201757190,
    "pwLogin" : true
  } ],
  "versionInfo" : {
    "version" : "5.10.1",
    "buildUser" : "jenkins",
    "buildTimestamp" : "20170319-2001",
    "gitHash" : "f226435f6fa5f545543c00245900ae43bea7a29c",
    "snapshot" : false
  },
  "managementService" : {
    "name" : "mgmt",
    "type" : "MGMT",
    "config" : {
      "roleTypeConfigs" : [ {
        "roleType" : "ACTIVITYMONITOR",
        "items" : [ {
          "name" : "firehose_database_host",
          "value" : "ed"
        }, {
          "name" : "firehose_database_name",
          "value" : "amon"
        }, {
          "name" : "firehose_database_password",
          "value" : "cloudera-scm"
        }, {
          "name" : "firehose_database_user",
          "value" : "cloudera-scm"
        }, {
          "name" : "firehose_heapsize",
          "value" : "813694976"
        } ]
      }, {
        "roleType" : "EVENTSERVER",
        "items" : [ {
          "name" : "event_server_heapsize",
          "value" : "813694976"
        } ]
      }, {
        "roleType" : "REPORTSMANAGER",
        "items" : [ {
          "name" : "headlamp_database_host",
          "value" : "ed"
        }, {
          "name" : "headlamp_database_name",
          "value" : "rman"
        }, {
          "name" : "headlamp_database_password",
          "value" : "cloudera-scm"
        }, {
          "name" : "headlamp_database_user",
          "value" : "cloudera-scm"
        }, {
          "name" : "headlamp_heapsize",
          "value" : "813694976"
        } ]
      } ],
      "items" : [ ]
    },
    "roles" : [ {
      "name" : "mgmt-ACTIVITYMONITOR-df3394bbbabb712ed98f181d208a0658",
      "type" : "ACTIVITYMONITOR",
      "hostRef" : {
        "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "6dcn4jotfbi1tfltnsq3m441r"
        } ]
      }
    }, {
      "name" : "mgmt-ALERTPUBLISHER-df3394bbbabb712ed98f181d208a0658",
      "type" : "ALERTPUBLISHER",
      "hostRef" : {
        "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "7l1kvcgo14gljqwii1n4f1gbm"
        } ]
      }
    }, {
      "name" : "mgmt-EVENTSERVER-df3394bbbabb712ed98f181d208a0658",
      "type" : "EVENTSERVER",
      "hostRef" : {
        "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "bsdqlvw48moqa1v07t3s03142"
        } ]
      }
    }, {
      "name" : "mgmt-HOSTMONITOR-df3394bbbabb712ed98f181d208a0658",
      "type" : "HOSTMONITOR",
      "hostRef" : {
        "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "anodz98s7ddpr581yoksptt5t"
        } ]
      }
    }, {
      "name" : "mgmt-REPORTSMANAGER-df3394bbbabb712ed98f181d208a0658",
      "type" : "REPORTSMANAGER",
      "hostRef" : {
        "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "ajd0vyyclcdwt21plg08udo0o"
        } ]
      }
    }, {
      "name" : "mgmt-SERVICEMONITOR-df3394bbbabb712ed98f181d208a0658",
      "type" : "SERVICEMONITOR",
      "hostRef" : {
        "hostId" : "590cc14f-5277-4acd-bc4b-97e21b58376e"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "9j4k8iidxr7oxseebux13tbf0"
        } ]
      }
    } ],
    "displayName" : "Cloudera Management Service"
  },
  "managerSettings" : {
    "items" : [ {
      "name" : "CLUSTER_STATS_START",
      "value" : "10/27/2012 12:00"
    }, {
      "name" : "PUBLIC_CLOUD_STATUS",
      "value" : "ON_PUBLIC_CLOUD"
    }, {
      "name" : "REMOTE_PARCEL_REPO_URLS",
      "value" : "https://archive.cloudera.com/cdh5/parcels/{latest_supported}/,https://archive.cloudera.com/cdh4/parcels/latest/,https://archive.cloudera.com/impala/parcels/latest/,https://archive.cloudera.com/search/parcels/latest/,https://archive.cloudera.com/accumulo/parcels/1.4/,https://archive.cloudera.com/accumulo-c5/parcels/latest/,https://archive.cloudera.com/kafka/parcels/latest/,https://archive.cloudera.com/navigator-keytrustee5/parcels/latest/,https://archive.cloudera.com/spark/parcels/latest/,https://archive.cloudera.com/sqoop-connectors/parcels/latest/"
    } ]
  }
}
