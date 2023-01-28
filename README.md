---
title: No-Code Deployment of Rancher Kubernetes on AWS
author: Zack Brady, Field Engineer
contact: zack.brady@rancherfederal.com
---


![rgs-aws-banner](/images/rgs-aws-banner.png)


# No-Code Deployment of Rancher Kubernetes on AWS GovCloud

### Table of Contents
  * [Introduction](#introduction)
  * [Challenges with Kubernetes](#challenges-with-kubernetes)
  * [Why Rancher on AWS](#why-rancher-on-aws)
  * [No-Code Deployment](#no-code-deployment)
  * [Industry Alternatives](#industry-alternatives)
  * [Parting Thoughts](#parting-thoughts)

## Introduction

Over the last few years, Kubernetes has revolutionized the world of infrastructure. From bare-metal servers to virtual machines to containers, Kubernetes has caused teams to re-evaluate their entire technology stack, in the best way possible.

## Challenges with Kubernetes

Most teams start off in the world of clusters and containers and quickly realize the complexity of the configuration, management, and deployment. From service meshes to ingress controllers to deployments to registeries and more, Kubernetes is not as simple as it seems. Here's when teams start exploring open-source tools, enterprise tools, or start diving down the deep dark path of internal development. 

For my teams, I always want to have balance between the additional workload, the features, and of course, the total cost. In Kubernetes, this is known as Managed Kubernetes or Kubernetes-As-A-Service (Kaas). As an industry, we keep seeing the numbers shift away from self-managed Kubernetes to managed Kubernetes. Here's where we can start to talk about how much easier the implementation and management of Kuberenetes becomes with Rancher.

## Why Rancher on AWS

Rancher is the complete software stack for anything and everything Kubernetes, it's the single pane of glass into your clusters.

... finish this

## No-Code Deployment

Seriosuly. It's zero code, zero configuration, and zero hassle.

There are a few options and variables you need to set, but it's a simple Amazon AWS Cloud Formation template. Currently, it's available at **http://tryranchergov.com** and in the Amazon AWS GovCloud (US) regions of **us-gov-east-1** and **us-gov-west-1**. 

![rancher-aws-setup](https://s3.amazonaws.com/rancherfederal.io/public/rancher-aws-setup.gif)

**and 8 minutes later...**

![rancher-aws-deployed](https://s3.amazonaws.com/rancherfederal.io/public/rancher-aws-deployed.gif)

As you can see, in less than 8 minutes, with four or five clicks, you have a fully deployed, configured, and highly available RKE2 Kuberenetes cluster with Rancher Multi Cluster Manager. It's awesome to see how low of a barrier of entry there is to getting started with Rancher and Kubernetes. 

## Industry Alternatives

Of course there are alternatives out there and you should always due your research and due diligence.

If you are considering offloading most of your management of Kubernetes, then there are a few viable alternatives such as Amazon Elastic Kubernetes Service (EKS), Azure Kubernetes Service (AKS), and Google Kubernetes Engine (GKE). If you are considering offloading some of your management of Kubernetes, then Red Hat OpenShift and VMWare Tanzu, may be an option for you.

## Parting Thoughts
