1: CM Monitoring Lab

What is ubertask optimization?

Where in CM is the Kerberos Security Realm value displayed?
Inside Administration -> Security -> Kerberos -> Configuration
Configuration Key:

**Kerberos Security Realm
**default_realm

My Host:

http://host:7180//cmf/settings?groupKey=config.common.kerberos.display_group&groupParent=#filtercategory=Settings&filterdisplayGroup=Kerberos&filterfreeText=realm


Which CDH service(s) host a property for enabling Kerberos authentication?

NameNode

How do you upgrade the CM agents?

Execute this steps host by host:

Stop agent:
      systemctl stop cloudera-scm-agent

Upgrade packets:

      yum upgrade cloudera-manager-agent

Start Agent:

      systemctl start cloudera-scm-agent

Give the tsquery statement used to chart Hue's CPU utilization?

select cpu_user_rate where roleType=HUE_SERVER


Name all the roles that make up the Hive service

        ZooKeeper:
          Server

        HDFS:

          NameNode
          DataNode
          JournalNode

        YARN:
          NodeManager
          ResourceManager

        HIVE:

          Hive Metastore Server
          HiveServer2

What steps must be completed before integrating Cloudera Manager with Kerberos?

      1 - Configuration of DNS and Reverse DNS Resolutions
      2 - Configuration of MIT KDC or another KDC  ( Server configurations )
      3 - Create a user with administrative privileges on KDC Server ( cloudera-scm user for example (addprinc cloudera-scm@REALM.CORP) )
      4 - Install the krb5-libs and krb5-workstation and openldap-clients on every node
      5 - Install or upgrade the Java JCE Polices ( for provide authentication with AES-256 (aes256-cts-hmac-sha1-96) )
      6 - Configure /etc/krb5.conf for every node
      7 - Make a test to verify if the firewall is allow ports 88 TCP/UDP, 464 TCP/UDP, 749 TCP, 754 TCP for every node
      8 - Configure the minimum user id ( to 500 or less then, it's depends of the KDC are you using.. MIT KDC, MSAD, RED HAT IDM... N)

