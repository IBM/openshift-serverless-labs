# Red Hat OpenShift Serverless

Red Hat OpenShift Serverless can be used to build, deploy and run event-driven applications that will start based on an event trigger, scale up resources as needed, then scale to zero after resource burst. These hands on exercises utilize  OpenShift Serverless to create serverless workloads on OpenShift.

## Pre-requisites

* a Free IBM Cloud account, to create a new IBM Cloud account, follow the instructions [here](https://ibm.github.io/workshop-setup/NEWACCOUNT/).
* a Red Hat OpenShift Kubernetes Service (ROKS) v4.5 using a cluster with admin rights and with the [knative-serving operator](https://docs.openshift.com/container-platform/4.5/serverless/installing_serverless/installing-knative-serving.html) installed.

## Labs

1. [Setup](setup.md),
2. [Deploy our First Application to Knative using the Knative Client (kn)](lab1.md),
3. [Deploy vnext Version and Apply Traffic Shifting](lab2.md),
4. [Tag revisions to generate custom app URLs](lab3.md),
5. [Knative from the Kubernetes Layer](lab4.md)

## Technologies

* Red Hat OpenShift Kubernetes Service (ROKS) v4.5
* Red Hat OpenShift Serverless components

## Contributors

* Belinda Venman, [beemarie](https://github.com/beemarie)
* David Carew, [djccarew](https://github.com/djccarew)
