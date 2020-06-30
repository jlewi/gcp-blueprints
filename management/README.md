# Management Blueprint

This directory contains the configuration needed to setup a management GKE cluster.

This management cluster must run [Cloud Config Connector](https://cloud.google.com/config-connector/docs/overview). The management cluster is configured in namespace mode.
Each namespace is associated with a Google Service Account which has owner permissions on 
one or more GCP projects. You can then create GCP resources by creating CNRM resources
in that namespace.

Optionally, the cluster can be configured with [Anthos Config Managmenet](https://cloud.google.com/anthos-config-management/docs) 
to manage GCP infrastructure using GitOps.

## Setting up the management cluster

For the latest instructions please see the website [https://master.kubeflow.org/docs/gke/deploy/management-setup/](https://master.kubeflow.org/docs/gke/deploy/management-setup/)

