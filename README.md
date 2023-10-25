# Cloud Marketplace 

This repo contains code required to publish and create 1 click deployable solutions to various cloud marketplaces. 

## AWS Marketplace

Currently, we have a cloudformation template which creates EC2 instance backed by a EBS volume which is used to store the data. The instance is pre-configured and starts running a catalyst node as soon as this template is deployed.