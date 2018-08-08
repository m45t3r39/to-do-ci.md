<br>Continuos Integration | TODO Application</br>
<br>Problem Description</br>
Setup CI for a project hosted on this repo. The above repository contains a basic Node based TODO Application.

<br>Expectations</br>
The setup should be a Jenkins master slave setup where slave should have below jobs ( jobs can be generated with Job DSL, and having a complete pipeline structure )

<br>Code stability job</br>
<br>Code quality job using sonar</br>
<br>Code coverage job</br>
<br>Deployment job which will deploy the app on a docker</br>
<br>The required configuration of the instance on which deployment would be done should be managed by a SCM tool( Chef, Puppet, Ansible ) of your choice.</br>

All the tasks should be done on docker.
