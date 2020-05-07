# Simple DevOps Project

This Repository is a collection of Implementation documents. 

### Purpose:
By following this repository you can able to setup a DevOps CI/CD Pipeline using
- git
- Jenkins
- Maven
- Ansible
- Docker &
- Kubernetes

Copy the output path as in step 3 which is value of the M2_HOME as below:

Update on create Java and Maven home: 
=====================================
export M2_HOME=/opt/apache-maven-3.0.5
export PATH=${M2_HOME}/bin:${PATH}
To set the Apache Maven environment variables only for current terminal, set the Apache Maven installation directory variable M2_HOME using export. Post that, set Apache Maven bin folder path into PATH variable.

To set the Apache Maven environment variables on server boot for all the users permanently, update /etc/rc.local file with the above export entries.

To set the Apache Maven environment only for specific user permanently, update respective user's .bash_profile file with the above export entries.

Verify by checking the variable value using below command:
==========================================================
echo $M2_HOME
echo $PATH
