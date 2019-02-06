## Project Proposal - Elasticsearch
Elasticsearch is an enterprise level distributed RESTful search engine based on Apache Lucene. It is open source, highly scalable and provides very fast, near real time searches. Elasticsearch can be used to search all types of documents. It is primarily developed in Java and comes with a powerful REST API interface. The Elasticsearch REST APIs are accessed using JSON over HTTP. Elasticsearch also supports clients in a wide variety of languages.

The basics of Elasticsearch are discussed in the [Elasticsearch concepts]( https://www.elastic.co/guide/en/elasticsearch/reference/current/_basic_concepts.html) page.   

The benefits of Elasticsearch in terms of query is it will let you combine and perform many different types of searches like structured as well as the unstructured searches. It also helps in working upon data which is based on geography or metrics. Irrespective of what type of data you have it will perform efficiently. Elasticsearch helps in analyzing the billions of log lines easily and provides aggregations which help you zoom out to explore trends and patterns in your data like show files where place is Chicago, aggregates data by days, aggregates data by geography and other different patterns. 

The main advantages of Elasticsearch are scalability, speed, multilingual, document oriented, autocompletion & instant search, and it is schema free. 


### Contributors
Users must sign a contributor license agreement as an individual user or a company, there by ensuring that Elasticsearch has right to use and distribute your work. Once signed you cannot withdraw from the agreement. Since it is open source software anyone can contribute to the project at the [Elasticsearch GitHub](https://github.com/elastic/elasticsearch) page. The contributors must follow the [contribution instructions](https://github.com/elastic/elasticsearch/blob/master/CONTRIBUTING.md) mentioned in their project open source page.

From the below graph we can analyze the number of people contributing to the Elasticsearch project since 2010. These statistics are from the Elasticsearch GitHub open source repository. From the graph we can observe the increase in the number of contributions for this repository by year.

![Contributions in GitHub](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Contributor%20GitHub.png)

The below statistics for contributors per month are based on the another Elasticsearch open source repository, [Elasticsearch open hub source page](https://www.openhub.net/p/elasticsearch).

![Contributions in OpenHub](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/OpenHub%20Contributor.png)

### Activity
Since the time it is developed, Elasticsearch has skyrocketed every year and is now currently one of the leading solutions. 
This project has nearly 50,000 commits by around 2,000 contributors and over a 2.5 million lines of code. These statistics are analyzed from the [Elasticsearch GitHub page](https://github.com/elastic/elasticsearch). 
The below statistics are according to the another opensource repository of Elasticsearch [Elasticsearch open hub source page](https://www.openhub.net/p/elasticsearch) 

![Activity of Elasticsearch](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Activity.png)

![Lines of Code](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Lines%20of%20code.png)

### Popularity
There are many organizations that are using Elasticsearch products such as eBay, Vimeo, Fermilab, Airbus, SAP Concur, Lyft, IEEE Globalspec, Citi, Fitbit and many others. We can see the increase in the popularity of Elasticsearch from year to year since the time it was developed. Since it is open source and free, the product popularity has increased worldwide. The benefits like a powerful API, flexible data storage, fast search, easy to scale, restful service, many great search engine features and many other features are keeping Elasticsearch one of the top competitors.

From the below statistics, we can observe the popularity of Elasticsearch year by year and regionally.

![Popularity of Elasticsearch](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Popularity.png)

![Popularity of Elasticsearch regionally](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Popularity%202.png)

### Languages Used
The language used to develop the Elasticsearch is Java.  There are many clients available that can connect to Elasticsearch. The official clients for Elasticsearch are Java, .NET (C#), PHP, Python, Apache Groovy, Ruby and other many languages. 

![Languages used in developing Elasticsearch](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Languages%20used.png)

### Platform Used
Elasticsearch requires at least Java version 1.8.0_131 or a later version in the Java 8 release series to run their project. It supports only Oracle’s Java and the OpenJDK. It is recommended to use same JVM version across all the Elasticsearch nodes and clients. They also tested running Elasticsearch successfully on the various platforms that are listed in their website. They also mentioned that it is also possible that it can work on other platforms that are not listed in their website.

[List of platforms page](https://www.elastic.co/support/matrix) consists of list of platforms that supports Elasticsearch.

### Documentation Sources
The main features and other detailed information including the guidelines for installing Elasticsearch are explained in the [Elasticsearch documentation page](https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html).
The [lectures about the features of the Elasticsearch](https://www.elastic.co/videos) page consists of all the videos about the products of the Elastic Stack.

### License
The core features in Elasticsearch are open source under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0.html), which is a permissive license from the Apache Software Foundation.  Elastic also provides paid features, through their X-Pack subscriptions.  The X-Pack features are also in the Elasticsearch GitHub repository, however these are published under the [Elastic License](https://github.com/elastic/elasticsearch/blob/0d8aa7527e242fbda9d84867ab8bc955758eebce/licenses/ELASTIC-LICENSE.txt).  So while the X-Pack code is open, it is not truly open source because of the license.

### Procedure for making contributions
Elasticsearch is an open source project so anyone can contribute their code through the GitHub source. Anyone can fork or clone their project from GitHub through the [Elasticsearch GitHub page](https://github.com/elastic/elasticsearch). Then they can make changes or add their new feature code to the project and run tests in the local machine. After testing fully, you can push and create pull request to the Elasticsearch. Then discuss the changes that you worked on with the elastic member. They will test the changes and if appropriate they will merge it to their master branch.

### Security History
Elastic has good resources and published information about vulnerabilities in the Elasticsearch software.  They have a page summarizing [security issues](https://www.elastic.co/community/security) on their website and a [forum](https://discuss.elastic.co/c/security-announcements) where new security announcements are posted.  Reporting new vulnerabilities to Elastic is as easy as emailing security@elastic.co.  

There have been relatively few security issues in the Elasticsearch software itself.  In the last five years only seven vulnerabilities have been published.  Since the X-Pack software was, until recently, more of a separate code-base, those vulnerabilities were categorized separately with nine flaws found since 2017.  In fact, all security bugs announced in 2017 were due to the X-Pack features.  The table below provides a quick summary of the number of vulnerabilities found in each of the past five years and the most significant severity according to CVSS v2.0. 

| Year | Elasticsearch | X-Pack | Highest Severity|
| ---- | ------------- | ------ | ----------------|
| 2014 | 2             | 0      | Medium          |
| 2015 | 5             | 0      | High            | 
| 2016 | 0             | 0      | N/A             |
| 2017 | 0             | 8      | Medium          |
| 2018 | 2             | 1      | High            |


### User Security Needs
Below are some basic security needs that various types of users would likely need from the software package and couple scenarios to highlight how Elasticsearch might exist in many different types of environments.

**User authentication** to protect data flow from unauthorized users and modifications.

**Data Integrity** to prevent accidental data loss, corruption and unintentional modifications.

    
    Scenario:  Being a responsible project manager I would like to use Elasticsearch for my 
    company. Our projects are driven by agile processes and I want to integrate Elasticsearch 
    with my ticket tracking tool to monitor the progress on project for each sprint.
    But I want authenticated users from my organization to view this progress and restric them 
    from altering any data in the cluster.  
    
   
  **Identity Access Management** to manage user activities on Elasticsearch cluster.
    
   Fine grained **user privileges** and attribute based access controls to prevent unauthorized access to Elasticsearch cluster.
   
    Scenario: As an IT Developer I use Elasctisearch on my version control to monitor the number 
    of commits by each developer for every project. All the developers can view their progress but 
    I would like to limit it to read permissions and restrict them from making any modifications 
    to the cluster. 
    
   **Access controls** on stored data procedures. 
      
      Scenario: If a client finds a bug in the application that gives access to Elasticsearch 
      this gives them access to data in all indexes and grab data that belongs to other clients.
      (This can be eliminated with the use of a commercial plugin called X-Pack Security). 
      As a user I except this to be a part of Elasticsearch.
       
   **Data Encryption** to protect user data (credit card information, email addresses, passwords) as it travels with in the clusters. 

   Secure (TLS/SSL) certificates to establish **trust** between nodes. 
    
    Scenario: I would like to monitor all the incoming IP requests to my home network and expect 
    Elasticsearch to securely encrypt my personal data, share my data to users I have given access.
        
   **Audit logging** for all unauthorized login attempts, nefarious network traffic trying to enter the cluster, detect false connections with no signatures.   

    Scenario: As a stakeholder of an ecommerce organization I expect an audit log to be able 
    to detect brute forced login attempts, unauthorized network access, denial of service attacks,
    and connections from unapproved clients to my Elasticsearch cluster. 
   
   Other security configurations are also important like making sure that clusters are hidden within private networks and only accessible to required applications and 
   manually disabling features that are not used by the application(e.g. default ports).

### Security Features
Since Elasticsearch is made up of many moving parts, it has various layers of security. X-pack security is the security provider that works on Elasticsearch on various levels. Following is a further description of the features:

_User Authentication_: Authentication services called realms, provided built in by X-pack, handles the process. There are some built in realms like native, LDAP, Active Directory, PKI, file, SAML. Also, one can built their own realm, which can then be plugged into X-pack.

_Authorization_: This refers to the process of identifying whether the requesting user is allowed to execute the request. It involves 5 sub-parts:
*	Secured resources
*	Privilege
*	Permissions (set of privileges)
*	Role (named set of permission)
*	User 

_Node/Client Authentication & Channel Encryption_: Encryption of data transmitted over the wire and certificate-based node authentication. This can be enhanced by configuring IP filters.

_Auditing_: Logs almost all activities that take place in the system so as to assist analysis in case of anomalies.


### Motivations
Elasticsearch is widely adopted in various industries like Netflix, Stack Overflow, LinkedIn, Accenture and Tripwire, amongst others. It has immense capabilities made possible due to the fact that it has a distributed architecture. It is interesting to dig into the possibility of security improvements of a search engine that has the scalability of thousands of servers and dealing with petabytes of data. Also, Elasticsearch is mostly built on Java, which all the team members are comfortable with.  

Some team members use or have used Splunk in that past.  The feature set of Elasticsearch is often compared to that of Splunk.  Learning a comparable tool that could potentially have a lower cost of ownership, or work to complement and maximize expensive investments in other solutions could be desirable to current or future employers.

### Project Links
* Team Repository: https://github.com/swrp/CYBR8420-SemesterProject
* Project Board: https://github.com/swrp/CYBR8420-SemesterProject/projects

