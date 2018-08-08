Continuos Integration | TODO Application
Problem Description
Setup CI for a project hosted on this repo. The above repository contains a basic Node based TODO Application.

Expectations
The setup should be a Jenkins master slave setup where slave should have below jobs ( jobs can be generated with Job DSL, and having a complete pipeline structure )

Code stability job
Code quality job using sonar
Code coverage job
Deployment job which will deploy the app on a docker
The required configuration of the instance on which deployment would be done should be managed by a SCM tool( Chef, Puppet, Ansible ) of your choice.

All the tasks should be done on docker.
