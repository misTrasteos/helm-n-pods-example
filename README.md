Sometimes you just want n equal pods to be created but without using a [ReplicaSet](https://kubernetes.io/es/docs/concepts/workloads/controllers/replicaset/)

This is an example of how to achieve this using Helm functions.

You can also run this example it with skaffold using `HELM_SKAFFOLD_RELEASE_NAME=skaffold-test skaffold dev --status-check=false`
