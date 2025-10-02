# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout ee98a8cdae93e278e00b49232c03eafdec6d53d0
kustomize build ./kustomize-guestbook
```
