# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 94e14e52f74361000734289a001ced42c2efbc7c
kustomize build ./kustomize-guestbook
```
