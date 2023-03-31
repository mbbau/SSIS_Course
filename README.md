# SSIS Course

This repository will host my notes about the course "SQL Server Integration Services" from [Adan Wilbert](https://www.linkedin.com/in/adam-wilbert/?trk=lil_instructor). The course can be found on LinkedIn Learning in the following [link](https://www.linkedin.com/learning-login/share?forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fsql-server-integration-services-2%3Ftrk%3Dshare_ent_url%26shareId%3D%252BXRQ%252FGFTT8awBN%252Br4uQK%252BA%253D%253D).


# Introduction: What is SSIS?

SSIS is a tool developed by Microsoft, and there is plenty of [documentation](https://learn.microsoft.com/en-us/sql/integration-services/sql-server-integration-services?view=sql-server-ver16) about it that you can read in order to get familiar with the tool.

In their page, Microsoft state that SSIS "is a platform for building enterpise-level data integration and data transformation solutions". This means that this tool will allow you to perform ETL (extract, transform, load) tasks from a wide variety of sources such as XML data files, flat files, and relational data sources, along many other tasks such as maintenance and administration.

In order to do this you will need to work in two different environments:
* SQL Server Data Tools (SSDT), used as a component of Visual Studio;
* SQL Server Management Studio (SSMS).

Within SQL Server Management Studio, you will have two instances (or as many as you open), one for the integration services and another one for the conection to the database engine. In the Integration Services instance, you will have access to two different folders, the *"Running Packages"* folder and the *"Stored Packages"* folder, as you can see in the next picture, taken from the course.

![SSMS Instances](SSMS%20Intances.png)

## SQL Server Data Tools (SSDT)

In order to create or manage SSIS packages, you will need SSDT. This is a part of Visual Studio, and you have to install it first. 

## Precedence Constraints

https://learn.microsoft.com/en-us/sql/integration-services/control-flow/precedence-constraints?view=sql-server-ver16

## Available tasks

There are several number of tasks that can be perform in every single step of a flow in a SSIS package. According to [the official Microsoft documentation about Integration Services Tasks](https://learn.microsoft.com/en-us/sql/integration-services/control-flow/integration-services-tasks?view=sql-server-ver16), *"Tasks are control flow elements that define units of work that are performed in a package control flow"*. 
There are different types of tasks you can perform within a data flow, such as:
 * Data Flow Task.
 * Data Preparation Tasks.
 * Workflow Tasks.
 * SQL Server Tasks.
 * Scripting Tasks.
 * Analysis Services Tasks.
 * Maintenance Tasks.
 * Custom Tasks.

For more information about this tasks, visit the previous link.