
# Usage

- This is just a convenient storage of source files.
- Learned  [Hortonworks Ambari](https://docs.cloudera.com/HDPDocuments/Ambari/Ambari-2.7.4.0/index.html) because it's too much mundane work to set up. Username/Password: admin/admin
- Using [Cloudera/Hortonworks HDP](https://www.cloudera.com/tutorials/sandbox-deployment-and-install-guide/3.html)
- To use: copy hadoop distribution directly into the repo folder
- Set up Hadoop environment and work from there. (only works on Linux)

```
	export HADOOP_HOME="/home/khoa/hadoop"
	export HADOOP_INSTALL=$HADOOP_HOME
	export HADOOP_MAPRED_HOME=$HADOOP_HOME
	export HADOOP_COMMON_HOME=$HADOOP_HOME
	export HADOOP_HDFS_HOME=$HADOOP_HOME
	export YARN_HOME=$HADOOP_HOME
	export HADOOP_COMMON_LIB_NATIVE_DIR=$HADOOP_HOME/lib/native
	export PATH=$PATH:$HADOOP_HOME/sbin:$HADOOP_HOME/bin
	export PDSH_RCMD_TYPE=ssh
```
- If namenode doesn't run (common issue in Hadoop 3.1.2), format it with ```hadoop namenode -format```

