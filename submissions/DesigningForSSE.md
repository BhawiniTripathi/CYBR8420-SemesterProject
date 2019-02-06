## Designing for Software Security Engineering
#### Data Flow: User Uploads Data
Level 0 DFD

![Level 0 for User Uploads Data](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/Threat%20Models/Analyst%20Pushes%20Data%20Into%20Cluster-Level-0.PNG)

#### Data Flow: System Uploads Data
Level 0 DFD

![Level 0 for System Uploads Data](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/Threat%20Models/Application%20Pushes%20Data%20Into%20Cluster-Level_0.PNG)

The complete threat report alongwith consolidated Level 1 diagram for system uploads data and user uploads data can be found <a href = "https://swrp.github.io/CYBR8420-SemesterProject/UpdatingDataToCluster.htm">here.</a>

#### Data Flow: Internal Cluster Communication
Level 0 DFD  
![Level 0 for Internal Cluster Communication](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/Threat%20Models/InternalClusterCommunication_Level_0.PNG)  

Threat Model/Level 1 DFD  
A full threat model and Level 1 data flow diagram has been completed <a href = "https://swrp.github.io/CYBR8420-SemesterProject/InternalClusterCommunication_ThreatReport.htm">here</a>.

#### Data Flow: Use Case: Analyst queries for data from cluster

Level 0 DFD

![Level 0 Analyst Querying for Data](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/Threat%20Models/AnalystQueriesForFraudReports.png)

A full threat model and Level 1 data flow diagram has been completed <a href = "https://swrp.github.io/CYBR8420-SemesterProject/AnalystQueriesForFraudReprts.htm">here.</a>


#### Data Flow: Alert to Fraud Analyst
![Level 0 Alert to Fraud Analyst](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/Threat%20Models/AlertToFraudAnalyst.PNG)

A full threat model and Level 1 data flow diagram has been completed <a href = "https://swrp.github.io/CYBR8420-SemesterProject/AlertToFraudAnalyst.htm">here.</a>



**Threat Model Analysis**  
As indicated in several sections of the threat models, Elasticsearch has a fairly robust security solution provided by the X-Pack features.  When doing the analysis, these security features directly addressed the STRIDE threats in many cases.  When thinking specifically about the defined data flows, the security features included, seem to be quite encompassing from the documentation available.  

Elasticsearch has methods to authenticate all cluster nodes, making spoofing difficult unless a member of the cluster is compromised.  Some security features, like strong encryption of all traffic, certainly minimize Information Disclosure threats, but also could reduce tampering.  Whitelisting and dedicated networks for cluster communication drastically reduce the risk of denial of service attacks.  Not allowing dynamic scripting can also lessen the risk from denial of service attacks.

Audit log generation options are available to ensure integrity of the log files and repudiation threats.  There is even an event type in the Elasticsearch system called "tampered_request" that specifically is logged if a tampered search request is discovered.  Various authentication methods including AD/LDAP integrations, help prevent repudiation threats in several analyzed data flows.

Role based access control and the default behavior of not running the software as root, but rather with standard user access, reduces the risk of elevation of privilege.  Document level access control, a granular set of user permissions, and input validation also minimizes threats in this area. 

Considering all of the controls researched and identified, we did not feel the threat model and analysis revealed any significant design issues.

#### Project Links
* Team Repository: https://github.com/swrp/CYBR8420-SemesterProject
* Project Board: https://github.com/swrp/CYBR8420-SemesterProject/projects/5
