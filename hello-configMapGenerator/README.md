## configMapGenerator

In this example we generate config maps from various text files (.properties,
.env) as well as from literal key value pairs using the `literals` list in the
configMapGenerator. We also show how to consume and reference the generated
ConfigMap in a Deployment.

To view or render the output (ConfigMap) run:

```bash
k kustomize ./
```
