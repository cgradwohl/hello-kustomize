## secretGenerator

https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/#secretgenerator

In this example we generate secrets from text files as well as from literal key
value pairs using the `literals` list in the secretGenerator. We also show how
to consume and reference the generated Secrets in a Deployment.

To view or render the output (Secret, Deployment) run:

```bash
k kustomize ./
```
