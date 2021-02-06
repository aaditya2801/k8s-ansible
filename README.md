# INTEGRATING: AWS PUBLIC CLOUD, ANSIBLE AND K8S MULTINODE CLUSTER

## This repo contains three ansile roles:

### 1. ec2-instance
### 2. master-node
### 3. worker-node

## command for provisioning ec2 instances:

### ansible-playbook myplaybook.yml (" here myplaybook.yml will run ec2-instance role for us ")

## command for the setup of multinode k8s cluster:

### ansible-playbook myplaybook1.yml (" here myplaybook1.yml will run master-node and worker-node role for us ")

## command for joining worker nodes with master node:

### ansible-playbook myplaybook2.yml (" here myplaybook2.yml will join worker node with the master ")

## command for deploying the multi tier architecture:

### ansible-playbook myplaybook3.yml (" here myplaybook3.yml will setup the HA arhitecture ")

#### * multi-tier directory contains yaml code for: secret and pod deployment for wordpress and mysql

