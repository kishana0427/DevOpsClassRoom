# Configuration Management

1. PUSH:
    * Ansible is a push model CM
    * Ansible requires user to login
    * Ansible requires python to be installed on all nodes

2. PULL:
    * Chef/Puppet is pull 
    * Chef requires agent to be installed on nodes
    * No user credentials required

![Preview](./images/pushnpull.png)


## What has to be done to configure Ansible?

![Preview](./images/overview.png)


## Idempotance
execution irrespective of number of times leads to same result
