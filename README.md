# Loan-approval
POC - Camunda

# How to start

1 - It's necessary to download Camunda.

https://camunda.org/download/

Follows "how to start" to see if it is being running correctly.

2 - It's necessary to download Eclipse:

https://www.eclipse.org/downloads/

and to install "Camunda BPMN 2.0 Modeler":

https://marketplace.eclipse.org/content/camunda-bpmn-20-modeler

optional (it's possible to use eclipse plugin only, but the modeler has more features and a better GUI):

https://camunda.org/download/modeler/

3 - First deploy:

There are two options:

a) you can follow tutorial in https://docs.camunda.org/get-started/bpmn20/project-setup/

b) or clone this repository and follow `deploy.sh` steps.

# Using Rest API
use this intemediate path to access camunda Rest API: engine-rest/engine/default or /camunda/api/engine/engine/default/
Example: http://localhost:8080/camunda/api/engine/engine/default/decision-definition/key/#{key}/evaluate
or http://localhost:8080/engine-rest/engine/default/decision-definition/key/#{key}/evaluate
