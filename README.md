## My project

## Project's reporter: Murashevich Mikhail

Group number: md-sa2-18-21

Description of application for deployment

SCM GitHub

Name: Joomla

Database: MariaDB

Webserver: Apache


## Pipeline

#
```bash
        /-------------http:8080----->>----\         /--> Slack
       /                                   \       /            /->(remote host_1 ansible host: joomla+Apache+MariaDB )
      /                                     \     /            /       
(localhost)-->push-->(GitHub)<-- clone --> (Jenkins) -- deploy --> (remote host_2 ansible host: joomla+Apache+MariaDB )
      \                                                                      /
       \                                                                    /
        \--------------- << -------http:80------ >> -----------------------/
```
#

Technologies which were used in project

Orchestration: Jenkins

Automation tools: Ansible

SCM: Github

Notification: Slack

Links

### Project [repository](https://github.com/mikevoice/project)
### Jenkinsfile [repository](https://github.com/mikevoice/pipe)
