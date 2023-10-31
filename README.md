PatientRMS System In Azure PatientRMS System Project This repository contains the
setup and configuration for an  PatientRMS system deployed on Azure. The project involves the creation of 
two virtual machines (Server1 and Server2) running Ubuntu Server, the installation of the Apache2 server, and the
setup of a MySQL database on both servers. Additionally, Azure Traffic Manager, Azure Monitoring Service are used to manage and monitor the deployment.
##Project Components Virtual Machines
#Server1: Apache2 server installed. PHP files uploaded to the HTML directory. MySQL database for the online food ordering system.
#Server2: Apache2 server installed. PHP files uploaded to the HTML directory. MySQL database for the online food ordering system.
##Azure Services: 1)Azure Traffic Manager: Configured to manage traffic between Server1 and Server2. Ensures high availability and load balancing for the online food ordering system.
2)Azure Monitoring Service: Alert rule set up to send notifications (email and SMS) when the system's resource usage exceeds 80% threshold.
##Deployment Instructions 1)Deploy two virtual machines running Ubuntu Server. 2)Install Apache2 and MySQL on
both Server1 and Server2. 3)Upload the PHP files to the HTML directory on both servers. 4)Configure the MySQL
databases for thePatientRMS system on both servers. 5)Set up Azure Traffic Manager to distribute traffic
between Server1 and Server2. 6)Configure the Azure Monitoring Service alert rule for resource monitoring.
The system is set to send email and SMS notifications when the resource usage exceeds 80%.
