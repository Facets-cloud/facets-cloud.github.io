# Concepts

## Stack

A stack is a technical blue print of your software product. It defines the resources (viz. databases, applications,
cloud resources) and the relationships between them. The definitions reside in a git repository, as version controlling
the stack is critical for rollbacks, tracking and attribution. Each resource type has a directory named after it. Each
resource is defined by a JSON file, usually placed in the instances directory of a resource type.

<img src="/documentation/media/stack.png" width="300" >


The above example defines 4 applications (backend, frontend, rockmongo and s3demo), 1 ingress (demoingress), 1 mongodb (
demomongo) and 1 s3 bucket (s3demo)

A stack defines a few other metadata like common environment variables, extensions used, disaster recovery policy and
allowed sizings etc

## Cluster

A stack can be used to create clusters in a cloud provider of choice. A cluster is essentially a Kubernetes cluster that
houses the defined Kubernetes resources and dedicated cloud resource instances defined in the stack.

## Control Plane

Control plane is the web UI to create, manage and operate stacks and clusters.

## Product Overview

![overview](../media/overview.png)