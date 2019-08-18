<img style="width:100%;" src="images/streams.png">

# Streams
Streaming Console

What is InsightLake Streams Console?
-----------

InsightLake Streams Console solution is part of InsightLake Data Platform. It provides an intuitive UI and allows users to manage and govern their streaming data.

Following features are provided:
* Manage multiple Kafka clusters from a centralized console
* Monitor cluster components brokers, zookeepers etc.
* Manage data stores (topics) & schemas easily
* Perform data balancing
* Manage client onboarding
* Manage data connectors
* Build streaming data flows quickly
* Explore realtime data
* Perform data transformations
* Apply fine grain security like data masking, tokenization etc
* Monitor JMX 
* Benchmark clusters etc.


Installation
------
* Download or clone the repository. 
* Run bin/insightlake command.
* Open browser with URL as http://localhost:8080/
* Change configuration in /conf folder to set different ports
* By default H2 database is used, you can change the database details in jdbc.properties file

Cluster Management
------
Simplified UI for Confluent Kafka Deployment & Cluster Management

* Deployment
Simple administration of Confluent Kafka cluster
Intuitive UI
Versioned Configuration
Rolling Upgrades
Security Management
Easy adding/removing hosts
Easy service management

<img style="width:100%;" src="images/streams-admin.png">

* Configuration
Manage Clusters, Brokers, Zookeeper & Perform Data Balancing

Agents make sure that configuration is in sync on similar nodes and alerts are generated in case of deviations. 
Centrally manage clusters
Manage DEV, QA, PROD, DR Clusters

<img style="width:100%;" src="images/streams-cluster.png">

Brokers - Check broker status and metrics
<img style="width:100%;" src="images/streams-broker.png">

Consumer - Status and metrics
<img style="width:100%;" src="images/streams-consumer.png">

Manage Kafka Users
Local
SCRAM
LDAP/AD
OAUTH

<img style="width:100%;" src="images/streams-user.png">

* Real time health check
Health checks can be performed on the cluster and complete report can be viewed or downloaded from the console. Report includes important suggestions in terms of priority.
Generate Health Check Report
OS Tuning Recommendations 
Config Recommendations

<img style="width:100%;" src="images/streams-health.png">

* Zookeeper Data
Admins can easily explore Zookeeper data tree.
<img style="width:100%;" src="images/streams-zk.png">

Perform data balancing
Reassign partitions

<img style="width:100%;" src="images/streams-databalance.png">

Perform preferred replica assignments

<img style="width:100%;" src="images/streams-replica.png">

Build multi-tenant cluster with quotas
View quota usage

<img style="width:100%;" src="images/streams-quota.png">

Tools
Generate sample data
Test producer & consumer
Run data generation for testing
<img style="width:100%;" src="images/streams-datagen.png">

Performance Tests – Producer | Consumer
Historical Comparisons


<img style="width:100%;" src="images/streams-perf.png">

Data Management
------
Explore real time data

<img style="width:100%;" src="images/streams-data.png">

* Connectors - Easy data integration
Bring data in and out of Kafka by utilizing many published connectors. Use visual flow to provision and monitor these connectors. Manage Kafka Integration
Manage connectors

<img style="width:100%;" src="images/streams-connectors.png">

* Streaming apps
Allows easy build of micro services and Kstream apps using visual designer.


* Data flows
Visual data flow designer allows creation of complex ETL pipelines.
Intuitive UI
Drag & drop components
Source
Sink
Enrichment
Workflow management

<img style="width:100%;" src="images/streams-designer.png">

* SQL
Simplified SQL centric data transformations
Join, Filter, UDFs etc.

Data explorer allows exploration of data using SQL queries.
<img style="width:100%;" src="images/streams-sql.png">

Governance
------
* Onboarding 
Manage Kafka applications
Govern data ownership
<img style="width:100%;" src="images/streams-apps.png">
Onboard new applications to Kafka platform and maintain a central repository to manage these apps. Admins can use this information to contact app owners for notifications, check what versions and technology app's clients are using.
It also allows app ownners to own topics and underline data, allow data users permissions to produce and consume data.
It also guides admins to standardize topic creation with right number of partitions, local replicas and inter cluster replication etc. It allows promotion of apps, data flows to higher environment.

* Schema management
Enterprise wide schema management
Create, update and maintain schema hierarchies
Audit trail of schema changes
Validate and test compatibility
Schema designer
Data catalog integration

<img style="width:100%;" src="images/streams-schema.png">
Schema management allows admins to create and update schemas, maintain versions and compatibility. It tracks schema change audit logs.
It also allows developers a read only view to adhere to approved schemas in the applications.


* Topic management
Topic Creation | Promotion
Data owner, consumers & producers

<img style="width:100%;" src="images/streams-topic.png">
Using topic management feature admins can create new topics, update topic parameters, flush topic data and perform topic related operations like preferred replica election and rebalancing of topic data. It also enables promotion of topics to higher environment.

* Data usage policies
Allows data governance teams to configure data usage policies.

* Lineage
Trace topic level data lineage

<img style="width:100%;" src="images/streams-lineage.png">
Allows easy tracking of data lineage visually in streaming environment.

* Data catalog
<img style="width:100%;" src="images/streams-catalog.png">
Allows various teams to create, manage and explore streaming data catalog. Example: Teams can find which data stores (topics) contains sensitive information and what those fields are.


Security
------
* Role based access
<img style="width:100%;" src="images/streams-acl.png">
RBAC feature enables admins to create different roles and grant access to features of streaming console to those roles. Console users can be assigned to these roles.

* LDAP/AD, Kerberos & SSO support
Console integrates login security using LDAP, File, Kerberos and SSO.

* Data masking & tokenization
Mask sensitive data
Disallow access

<img style="width:100%;" src="images/streams-dlp.png">
Security policies can be easily defined to mask or tokenize in-flight data.

* Audit logs
Comprehensive audit logs are captured, which could be explored easily.

Monitoring
------
* Dashboards
Build real time dashboards backed by Kafka

<img style="width:100%;" src="images/streams-dashboard.png">
Look at pre-defined templates to make sure cluster is healthy and stable.

* JMX Monitoring
JMX
Alerts
Consumer Lag
Producer & Consumers
Cluster components

<img style="width:100%;" src="images/streams-jmx.png">

Role based access on UI
Admins, Developers, Business Users roles

<img style="width:100%;" src="images/streams-acl.png">
Monitor important JMX metrics and build dynamic dashboards.

* Alerts
Create and manage alerts
Perform historical analysis

<img style="width:100%;" src="images/streams-alert.png">
Provision alerts on important metrics breaching specified thresholds.

* Logs
Monitor audit and system logs.

Machine Learning
------
* Anomaly Detection
Perform real time anomaly detection, clustering and window based machine learning models.

License
------
InsightLake Data Explorer is a commercial product but distributed to be used freely. Please contact contact@insightlake.com for details.
