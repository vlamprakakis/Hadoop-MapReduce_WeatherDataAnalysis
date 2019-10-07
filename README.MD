# PROJECT DESCRIPTION

Process and analyze a large set of meteorological data. The meteorological data refer to the temperatures recorded in the city of Milan. This data will be applied to the MapReduce programming model to draw conclusions about the average maximum temperature of the months of the year for a number of years. 

Editing has been done with Hadoop which supports distributed large data processing and provides implementation of the MapReduce programming model.
The datasets include all days from 1972 to 2013, ie the temperatures recorded daily for 42 consecutive years.

# PROJECT IMPLEMENTATION ENVIRONMENT 

To accomplish this task, a computer cluster was created on the Cloud, specifically Microsoft's AZURE service. The cluster was set up on HDInsight, the online platform offered by AZURE for data analysis. Through the HDInsight provided by Hadoop as an open-source framework, the HDFS file system has been set up and our program code is running.

# CLUSTER NETWORK AND SPECIFICATIONS

In order to perform the necessary simulation of distributed data processing on more than one machine, a computer network consisting of 5 virtual machines was set up.
Below is a summary of the role assigned to each virtual machine to execute the program in the Hadoop environment.
5 nodes
2 Head Nodes. Master: Namenode and Jobtrackers - the second node needed for the first Head Node failure cases
4 Cores, 7GB RAM / node
3 Worker Nodes. Slaves: Datanodes and TaskTrackers
4 Cores, 7GB RAM / node
Cluster type: Hadoop 2.7 on Linux
