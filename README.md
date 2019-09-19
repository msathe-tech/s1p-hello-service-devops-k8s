# s1p-hello-service-devops-k8s

This repo has deployment and service YAMLs for s1p-hello-service.
The files are separated based on target env - dev or prod.

```spinnaker-dev.yaml``` contains deployment and service YAML for s1p-hello-service

This file is a trigger for spinnaker CD pipeline.
Anytime a change is done to ```spinnaker-dev.yaml``` the CD pipeline will trigger a deploy on K8s.

