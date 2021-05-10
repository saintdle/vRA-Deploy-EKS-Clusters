# Using vRealize Automation Cloud Code Stream to Deploy AWS EKS Clusters, register endpoints with vRA and Clusters with Tanzu Mission Control

This repository contains the configurations for the following;
- Create a Code Stream Pipeline
  - Create a AWS EKS Cluster
  - Create EKS cluster as endpoint in both Code Stream and Cloud Assembly
  - Register EKS cluster in Tanzu Mission Control
  
Prerequisites
- vRA Cloud access
  - The pipeline can be changed easily for use with vRA on-prem
- AWS Account that can provision EKS clusters
- Docker host to be used by Code Stream
  - Ability to run the container image: [saintdle/aws-k8s-ci](https://hub.docker.com/r/saintdle/aws-k8s-ci)
- Tanzu Mission Control Account that can register new clusters

Getting started
- https://veducate.co.uk/vra-deploy-eks-tmc/
