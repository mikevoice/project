# My project

## Project's reporter: Murashevich Mikhail

---

## Group number: md-sa2-18-21

## Description of application for deployment

### Name: Joomla

### SCM GitHub 

### Webserver: Apache

### Database: MariaDB

## Pipeline

#

#        /------------http:8080------->>----------\         /-----> Slack
#       /                                          \       /
#      /                                            \     /                   
#(localhost) ---> push --->(GitHub)---> clone ---> (Jenkins) --- deploy ---> (remote local ansible host: joomla+Apache+MariaDB )
#      \                                                                              /
#       \                                                                            /
#        \----------------------- << -------http:80------ >> -----------------------/

#

## Technologies which were used in project

## Orchestration: Jenkins

## Automation tools: Ansible

## SCM: Github

## Notification: Slack

links

### Github [repository](https://github.com/mikevoice/project)
### Jenkinsfile [repository](https://github.com/mikevoice/pipe)
