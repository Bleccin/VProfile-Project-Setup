# VProfile-Project-Setup
In this project I will be setting up Multi Tier Web Application Stack for a socal networking site. The stack is written by developers in Java language.
Setup will be locally on my machine.

PROJECT SCENARIO:
Working on a project with variety of services such as Memcached, MySQL, Nginx etc. There is a runbook to setup these services but I'm not comfortable in making changes in the real servers. I will like to setup all the stacks locally on virtual machines. However, the local setup is complex, time consuming and not repeatable. 

SOLUTION:
We can have a local setup but it would be automated, repeatable. I will use Infrastructure as code (IAAC) to complete this.

TOOLS:
1. Hypervisor: Oracle VM VirtualBox
2. Automation: Vagrant
3. CLI: Git Bash
4. IDE: Vscode

OBJECTIVES:
1. Setup VMs locally.
2. Baseline for upcoming projects
3. Real World project setup locally (for R & d)

ARCHITECTURE OF PROJECT SERVICES:
1. NGINX => Web Service
2. TOMCAT => Application Server
3. RABBITMQ => Broker/Queuing Agent
4. MEMCACHED => DB Caching
5. MYSQL => SQL Database

<img width="495" alt="image" src="https://github.com/user-attachments/assets/8a15f44d-5f71-4c1c-b7a9-70fd18a52eac">

Setup should be done in below mentioned order
1. MySQL (Database SVC)
2. Memcache (DB Caching SVC)
3. RabbitMQ (Broker/Queue SVC)
4. Tomcat (Application SVC)
5. Nginx (Web SVC)

ARCHITECTURE OF AUTOMATED SETUP:
1. VAGRANT
2. VIRTUAL BOX
3. GITBASH


