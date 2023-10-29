# portainer-stacks

A repo to manage my self-hosted resources in [Portainer](https://www.portainer.io/).

## Description

Within this repo, I keep the configuration for many docker-compose stacks that I run via Portainer. Portainer has a built-in functionality to watch a git repo for said stacks (which are defined as Applications), and update the deployments if it notices modifications in the git repo. Effectively this gives me a fairly simple to manage GitOps flow, that doesn't require me to maintain the overhead of Kubernetes and ArgoCD in my self-hosted envirmonment.

