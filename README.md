# syslog_alert

A Spark streaming application that uses Kafka as a streaming platform. The program reads input from a topic of syslog messages, determines if the message exceeds a threshold, and if so creates and produces a record to an output topic of alerts

The program uses [MapR's Sandbox for Hadoop](https://mapr.com/products/mapr-sandbox-hadoop/download/) to run.

To run the program go over the [getting_started_guide.txt](https://github.com/enrique-cardenas/syslog_alert/blob/master/getting_started_guide.txt)


This program was an assignment for the CS185C: Solving Big Data Problems course taught by James Casaletto at San Jose State University.
