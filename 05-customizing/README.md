### Customizing

Kustomize supports `StrategicMerge` and `Json6902` using the patches field.

We can patch from a number of sources including inline string or a file and we
may target single or multiple resources.

The `patch` field of the `kustomization.yaml` file can select resources to patch
by group, version, kind, name, namespace, labelSelector and annotationSelector.

It is considered best practice to create small patches that do one thing. The
target resource is matched using group, version, kind, and name fields from the
patch file.

Run kubectl kustomize ./ to view the resources.
