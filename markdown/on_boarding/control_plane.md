# Getting Facets Control plane

You will need the Facets control plane to start spawning clusters in cloud of your choice. There are two types of
control planes which can be deployed by Facets.

## Private

Facets.cloud would deploy a private control plane in a AWS Account owned by you and you can create and manage stacks and
clusters using the same.

This would deploy a bare minimum K8s cluster to host the control plane stack for you.

> **Interesting Fact:** Even the control plane is a Facets stack.

## Shared

Facets.cloud will host a control plane in its own cloud and will pass on the credentials to you to manage the stacks and
clusters.

## Getting access

Right now the access to control plane is on invite basis only and you can contact us to get a trial account with us.