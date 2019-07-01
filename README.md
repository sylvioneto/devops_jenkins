# devops_jenkins

## author: sylvio.pedroza@gmail.com

## description
This project creates a local devops environment for jenkins pipeline development and test.
It has a tomcat and sonarqube in order to develop pipelines to test java deployment and code quality reports.

## usage
1. Install docker
2. Install ansible 2.8.1
3. Make sure dir /opt/jenkins_home has rw permissions
4. Download the repo, and run the playbook from ansible dir: $ ansible-playbook config/playbook.yml
5. Access the applications:
- Jenkins http://localhost:8180
- Sonarqube http://localhost:9000
- Tomcat http://localhost:8080