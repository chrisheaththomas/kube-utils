# Kubernetes utilities

Utility scripts for getting, deleting, jumping on to and port-forwarding to pods using the current directory as the context for Kube app.

Example usage:

```sh
$ cd piano-nectar-sign-up
$ source bashpod
```

Depends on the `kubetest` and `kubeprod` aliases for `kubectl --kubeconfig=<kube config file>`
