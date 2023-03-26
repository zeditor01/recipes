# Recipes
Publishing Recipes for Zeditor Mainframe Tasks

This project is intended as a source for Git Pages to create a website for publishing articles on getting things done on z/OS.

change made from Macbook.


## Contents Notes

```
Zeditor.org 

Recipes & Worked Examples for Getting Things Done on z/OS


Data Analysis of Mainframe Data at Rest.
- Using industry-standard tools ( Jupyter, python, graphDB, etc... )
- with a range of SQL and REST APIs
- exploiting SQL Data Insights ( AI-enabled query )
- without needing a network of "support servers" surrounding IBM Z 
- and extending query reach beyond Db2 z/OS to IMS, VSAM and other data sources on IBM Z

Z Data in Motion, if you choose to copy Z Data to other platforms
- data replication using Infosphere CDC from IMS, Db2 and VSAM to Kafka and other LUW targets
- data replication and publishing between Db2 databases
- Operations and Monitoring approaches

Machine Learning with IBM Z transaction and data systems
- Point of View: When to deploy AI patterns on Telum-enabled IBM Z, and when to use GPU-enriched Intel systems.
- Tensorflow Serving on IBM : deployment patterns
- Watson Machine Learning for z/OS : deployment patterns 

Db2 z/OS Capabilities
Walk-thru a series of worked examples for database administration with Db2 z/OS 
- SQL Language 
- Db2 Utilities
- Online Schema Evolution
- Temporal Data 
- Transparent Archive 

```

## Media Notes

```
zedtor01/recipes is the HTML landing page introducing the content domains
- Z Data Analysis
- Z Data in Motion
- Machine Learning with IBM Z
- Db2 z/OS Capabilities

youtube channel ( zeditor01 )  with 4 series of videos at first 

further markdown github repositories for the 4 domains

ZVA image for HoLs

Washington Systems Centre for zCX stuff and performance



```


## Workplan

- Z Data Analysis
- Z Data in Motion
- Machine Learning with IBM Z
- Db2 z/OS Capabilities


### Workplan 1 : zData Analysis

```
Data Analysis of Mainframe Data at Rest.
- Using industry-standard tools ( Jupyter, python, graphDB, etc... )
- with a range of SQL and REST APIs
- exploiting SQL Data Insights ( AI-enabled query )
- without needing a network of "support servers" surrounding IBM Z 
- and extending query reach beyond Db2 z/OS to IMS, VSAM and other data sources on IBM Z
```

1. Verify & Improve SQLDI ( better data ; better sample queries ; Lvl3 + Lvl 4 )
2. Deploy graphDB in zCX
3. Deploy odbc & jdbc clients & REST services 
4. Deploy best version of Jupyter 
5. Deploy DVM & Create IMS & VSAM sources 
6. Wrap it up in a structured guided tour


### Workplan 2 : z Data in Motion 

```
Z Data in Motion, if you choose to copy Z Data to other platforms
- data replication using Infosphere CDC from IMS, Db2 and VSAM to Kafka and other LUW targets
- data replication and publishing between Db2 databases
- Operations and Monitoring approaches
```

1. Re-build & document CDC Tour de Force
2. Build & document QREP Tour de Force
3. Build & Document zCX Monitoring



### Workplan 3 : Machine Learning with IBM Z 

```
Machine Learning with IBM Z transaction and data systems
- Point of View: When to deploy AI patterns on Telum-enabled IBM Z, and when to use GPU-enriched Intel systems.
- Tensorflow Serving on IBM : deployment patterns
- Watson Machine Learning for z/OS : deployment patterns 
```

1. Tensorflow Serving Deploy & Serve
2. Jupyter Analysis, Build & Train Model 
3. WMLZ Deploy


### Workplan 4 : DB2 zOS storyboards

```
Db2 z/OS Capabilities
Walk-thru a series of worked examples for database administration with Db2 z/OS 
- SQL Language 
- Db2 Utilities
- Online Schema Evolution
- Temporal Data 
- Transparent Archive 
- etc... 
```

Use Db2demo as my inspiration 

