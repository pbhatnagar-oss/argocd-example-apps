# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout c14dd487d19e0f9ea6311625d21dda736b9c1a15
kustomize build ./kustomize-guestbook
```
