
1.0 PROJECT IDENTIFICATION 

Project Name: INFT3000 Capstone - SB-GARD Suite™ 

Description: 

Multiple PowerShell security tools that enable user-friendly intrusion detection notifications and reports. These tools are to support better awareness of potential inconsistencies within a network and allow for greater transparency on events recorded on a given network/machine. 

Background: 

Six cybersecurity students, leveraging their learned skillset to create a year-end project for Capstone to prepare and deliver documentations, presentations and a final product using a variety of platforms. 

A suite of security tools will be developed with intent for them to be used by security analysts that could benefit from additional monitoring and notifications of changes in their environment. Prerequisites for the project will include knowledge in PowerShell scripting, project management skills, and database development knowledge. 

The tools will be developed for the Windows OS platform. Pseudocode will be written initially for the suite of services with plans to iterate on as the project moves forward and expectedly changes. We will design a website where we can share our features and our story with the public. 

2.0 PROJECT DESCRIPTION

2.1 Authorization_Logon

A script that could accurately alert on if a logged in user was part of an approved list of users and based on the condition, either continue or alert Admins on the unauthorized logon. Another feature we wanted in our script was to make the alerts that the admins will receive to be informative and dynamic by supplying details in it like the user’s AD username, the machine host name, and the IP address. The script is sent to the Administrator shared email account at sbgard@protonmail.com via an SMTP server that the Capstone group created.

2.2 Service_PID

An application that regularly scans the computers running or installed services and compares them to the generated baseline database created on installation. If any discrepancies are detected a log is generated and documented within a custom database. For alerting, the application then collects the relevant information and sends via email to the corporate IT support team with ticketing references.

2.3 Routing_Table

STUFF
