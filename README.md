# Devops-Course
# What is devops 
Devops is not a technology it is a culture 
Devops is set ot practices , tools and cultural philosophy that automate and integrate the processes between software development nd it teams 
Devops is used throughout software development life cycle 
<img width="507" height="213" alt="image" src="https://github.com/user-attachments/assets/969a5508-cd3b-42c2-ae04-53f8fb2047f4" />

# SDLC
The process of developing and delivering software project called SDLC
In SDLC we have several phases 
Requirement gathering
Requirement analysis 
Design/planning
Coding /implementation 
Testing
Deploy
Deliver 
Maintenance


# Waterfall methodology -
Waterfall is linear methodology to develop and deliver projects
Everything will happen step by step
We will move only in forward direction 
Requirement is fixed 
Budget is fixed 
Client will see the project at the end 
Client involvement is very less

<img width="303" height="218" alt="image" src="https://github.com/user-attachments/assets/94735ca5-6a9d-4bee-ac67-b0eb203a9e2d" />


# Agile methodology 
Agile is iterative approach
Development and testing will happen parallelly
Client involvement will be very high
We will deliver project in multiple releases (sprints)
For every release we will take client feedback
Requirement are not fixed
Budget is not fixed
Project development , testing and delivery is very frequent is agile
Using devops culture we can adopt agile methodology very easily 

<img width="542" height="207" alt="image" src="https://github.com/user-attachments/assets/168f02db-8cb3-40c8-975c-d3a5bc78cbbb" />


# Tools for Devops 
Build tools 
Ant /maven /gradle

Repository tools 
SVN/github/bitbucket

Code review tools 
PMD/Sonarqube/sonarlint

Code deployment tools 
Jenkins/UDeploy

Configuration tools 
chef/ansible

Containerization tools 
docker

Orchestration tools
k8s

Monitoring tools 
Nagios /grafana

Project management tools 
JIRA

<img width="552" height="187" alt="image" src="https://github.com/user-attachments/assets/957361b7-c444-48fb-9db7-d1f28cdf0d9b" />
------------------------------------------------------------------------------------------


Devops Process 
Developer gives a piece of code
Devops engineer has to copy this code on to the server
<img width="461" height="237" alt="image" src="https://github.com/user-attachments/assets/eba6c0a2-c570-4070-9f08-8326733ece79" />



<img width="606" height="346" alt="image" src="https://github.com/user-attachments/assets/68ca4902-ec0d-43d2-8fe1-fabc116c5f4d" />


<img width="571" height="291" alt="image" src="https://github.com/user-attachments/assets/e16d740f-6d5b-4a03-b28b-45f4ca2940ae" />



<img width="586" height="362" alt="image" src="https://github.com/user-attachments/assets/4ce4a06b-d341-49c1-ac6f-bf1accfe2544" />



<img width="578" height="295" alt="image" src="https://github.com/user-attachments/assets/1ea67cb3-c611-4e28-b5b9-af426ebddc16" />



<img width="592" height="310" alt="image" src="https://github.com/user-attachments/assets/e7501d87-3b9c-429f-831e-14743758a49a" />



<img width="596" height="308" alt="image" src="https://github.com/user-attachments/assets/6ca45c40-01cd-4b17-842a-a484625d4d23" />



<img width="576" height="326" alt="image" src="https://github.com/user-attachments/assets/ccf3486b-8f94-4652-8587-535d4dd7e4dc" />




<img width="612" height="651" alt="image" src="https://github.com/user-attachments/assets/33aa7ad9-831b-45f0-8bd0-003f0706a8c1" />





---------------------------------------------------------------------------------------------
ineuron 
**Lec 1 **
# What is devops ? 
It is a cultural practice in an organization by development team and operation team 
To use each others tool to smooth out the process of software delivery

Code
Test 
Deploy
Operation 
Operation team uses a lot of dev tools 

If you want to implement devops in an organisation you need to lean 
Core values 
Core idea 
Methods



# What is DevOps CAMS ?
CAMS means Culture , automation , measurement and sharing


Culture 
Talk to each other 
People over process over tools
Always value people then process and then tools 

Automation 
Not just a chef or puppet
thousands of servers are impossible to manage but do you need a thousand servers ?
How much can you automate or should you automate ?

Measurement 
Measure to improve
It’s not just about infra measurement 
Business measure ,client activity and other pointers
Recovery time , cycle time are obvious but its important to measure and incentivise it 

Sharing


# DevOps Working in 3 ways 

Flow thinking 
Developer ship code to branch 

Amplify feedback 
Ops team explain developer to features , design and they are working on it and giving feedback

Experiment and learn 

Devops Lifecycle

# DevOps Terms

Provisioning
Server is ready with os , software and networking

Deployment 
Adding or upgrading software on server 

Orchestration
Coordinated operations on multiple systems

Configuration management 
Managing server configuration via files such as ram , space,dependency softwares

Imperative (procedural)
Commands to produce desired state

Declarative 
Desired state is defined and tools will achieve it 

Idempotent 
Repeat execution and same result

Blue green deployment 
Identical deployment used as switch

Continuous integrations 
Build and unit test at every checkin

Continuous delivery 
Deploy on production live environment at every checkin

Continuous deployment 
After unit testing deploy changes to production in small batches 


**Lecture 2 Linux **
Resources Required 
virtual box 6.x
Centos iso 7 or above

Configure centos in virtual box

Basic of Linux
Linux is open source operating system 
The source code of linux is easily available for everyone
Linux provides security
Older computer systems can be revived using linux
Customization can be done using linux
Various distributions can be done using linux
Linux is free to use
Cost of linux is low
Large community support


Linux system having different packages —--> package manager is there (Debian /RPM/YUM) —---> centos use yum —-----> they distribute packages using repository 


Repository check package meta data and package dependencies and check it will compatible to you or not 

Difference between RPM and YUM

RPM 
YUM
Redhat package manager
Yellow dog updater
It installs only single package at a time
It install multiple package at a time
RPM cannot resolve dependencies
It can resolve dependencies automatically
Cannot rollback with RPM
Yum can rollback any changes 

Architecture of Linux

Hardware (it interact with your os and it cannot do it directly so it will communicate with kernel and os is communicate with hardware with the help of kernel)

Hardware >>>>>>>kernel>>>>>>shell >>>>>>>applications and utilities


<img width="541" height="422" alt="image" src="https://github.com/user-attachments/assets/8cb1853e-4bd3-4f12-bcc8-7bb9051480e1" />

# Commands used in linux
Whoami
ls 
Pwd
cd
Touch 
Mkdir
Ls -l

Task : 
Go to directory of desktop and there i need to make a directory named as ineuron and inside that directory create a text file named devops.txt and change the chmod permission of this text file to 777
Whoami
ls 
Pwd
cd
Touch 
Mkdir
Ls -l

User       Group       other
 7              7               7

Read —-> 4
Write —--> 2
Execute —--> 1
4+2+1= 7 

Chmod 467 devops.txt


