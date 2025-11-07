### Composing Resources

https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/#composing

Kustomize offers a solution to easily compose resources from different files.

Simply use the `resources` field in the `kustomization.yaml` to include them in
the outputted configuration i.e. a Deployment and a Service.

Running `kubectl kustomize ./` outputs both the Deployment and the Service
objects. So this one command can produce multiple resources that are
independently defined.
