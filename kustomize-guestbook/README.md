# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout f33f3373e5914a7801134aeabaed296cfab8dd14
kustomize build ./kustomize-guestbook
```
