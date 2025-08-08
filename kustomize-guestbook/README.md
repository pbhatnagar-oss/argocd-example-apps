# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout f04bf609a11e88c604ced91528497a6c4a80e1bd
kustomize build ./kustomize-guestbook
```
