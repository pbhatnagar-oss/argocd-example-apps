# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 27682d7fe540c6666d1716170a4a3a24abf74f5a
kustomize build ./kustomize-guestbook
```
