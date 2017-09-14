## Kubernetes pod creationg and scaling-up tests

The yaml file(s) in the yaml/ directory are used to create test pods
and then scale them up by increasing the number of replicas.
The test is handled by Jenkins using the podName, replicaCount, and
replicasCreationInterval build parameters.
See the jenkins-library repository.
