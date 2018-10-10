# Cloudera Cluster Auto Setup Scripts
Auto install cloudera cluster


## Quick start
*Read this in other languages: [English](README-en.md), [简体中文](README.md).*

1. prepare your Linux server[*](#quick-start-note) with a fresh install of Redhat 7 or CentOS 7.
2. prepare the necessary packages, eg.oracle jdk, mysql jdbc driver etc...
3. prepare the cluster ip list alongside this script
4. exec the command: 
```bash
sudo sh setup_cdh_cluster.sh
```

## Todo
1. fix the /etc/profile repeat issue
2. fix the /etc/rc.local repeat issue
3. fix the /root/.ssh/authorized_keys repeat issue
