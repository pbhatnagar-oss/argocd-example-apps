# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 0f4febb1232ad1ec772bcfdab10486d5f4d818a7
kustomize build ./kustomize-guestbook
```
