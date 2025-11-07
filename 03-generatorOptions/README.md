### generatorOptions

https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/#generatorOptions

We use `generatorOptions` to control the behavior of the generated ConfigMaps
and Secrets.

For example we can change the suffix naming schema of the hash, as well as
setting a convention for "cross-cutting" fields like the namespace, prefix or
suffix conventions. label sets, and annotations.

Run `kubectl kustomize ./` to view the generated output.
