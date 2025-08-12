# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 42dc502da2fdacab9665ec04157f5ee9c14bf094
kustomize build ./kustomize-guestbook
```
