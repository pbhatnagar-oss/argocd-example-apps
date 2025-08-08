# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 08568cfa0343f3f5b4a4e43b5c69893044f2a56e
kustomize build ./kustomize-guestbook
```
