![helm](https://user-images.githubusercontent.com/60067670/119780491-83081580-bee7-11eb-91b2-9234602419f6.png)


## What is Helm??
Helm is the package manager for Kubernetes, which is used for automating creation, packaging, configuration, and deployment of applications and services to Kubernetes Cluster.

Simply put, If Kubernetes were an operating system, Helm would be the package manager. Ubuntu uses apt, CentOS uses yum, and Kubernetes uses helm. Each deployment of a chart is a Helm release.

## Why do we need Helm?
One of its many advantage is, that, Helm keeps track of the versioned history of every chart installation and change.

Rolling back to a previous version or upgrading to a newer version can be done easily with a few commands which allows software developers to deploy and test an environment in the simplest possible way.

## Prerequisites required for this deployment:
➤ A Kubernetes Cluster.

I have one multinode cluster already set-up on AWS.

*Note- Package is called Chart in Helm*
