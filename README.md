<img style="width:100%;" src="streams.png">

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
* Configuration
Agents make sure that configuration is in sync on similar nodes and alerts are generated in case of deviations. 

* Real time health check
Health checks can be performed on the cluster and complete report can be viewed or downloaded from the console. Report includes important suggestions in terms of priority.

* Zookeeper Data
Admins can easily explore Zookeeper data tree.

Data Management
------
* Connectors - Easy data integration
Bring data in and out of Kafka by utilizing many published connectors. Use visual flow to provision and monitor these connectors.
* Streaming apps
Allows easy build of micro services and Kstream apps using visual designer.

* Data flows
Visual data flow designer allows creation of complex ETL pipelines.
<img style="width:100%;" src="streams-designer.png">

* SQL
Data explorer allows exploration of data using SQL queries.


Governance
------
* Onboarding 
Onboard new applications to Kafka platform and maintain a central repository to manage these apps. Admins can use this information to contact app owners for notifications, check what versions and technology app's clients are using.
It also allows app ownners to own topics and underline data, allow data users permissions to produce and consume data.
It also guides admins to standardize topic creation with right number of partitions, local replicas and inter cluster replication etc. It allows promotion of apps, data flows to higher environment.

* Schema management
Schema management allows admins to create and update schemas, maintain versions and compatibility. It tracks schema change audit logs.
It also allows developers a read only view to adhere to approved schemas in the applications.

* Topic management
Using topic management feature admins can create new topics, update topic parameters, flush topic data and perform topic related operations like preferred replica election and rebalancing of topic data. It also enables promotion of topics to higher environment.

* Data usage policies
Allows data governance teams to configure data usage policies.

* Lineage
Allows easy tracking of data lineage visually in streaming environment.

* Data catalog
Allows various teams to create, manage and explore streaming data catalog. Example: Teams can find which data stores (topics) contains sensitive information and what those fields are.


Security
------
* Role based access
RBAC feature enables admins to create different roles and grant access to features of streaming console to those roles. Console users can be assigned to these roles.

* LDAP/AD, Kerberos & SSO support
Console integrates login security using LDAP, File, Kerberos and SSO.

* Data masking & tokenization
Security policies can be easily defined to mask or tokenize in-flight data.

* Audit logs
Comprehensive audit logs are captured, which could be explored easily.

Monitoring
------
* Dashboards
Look at pre-defined templates to make sure cluster is healthy and stable.

* JMX Monitoring
Monitor important JMX metrics and build dynamic dashboards.

* Alerts
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
