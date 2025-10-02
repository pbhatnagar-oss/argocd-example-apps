# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 95d35edec53a00a65c9e32327580e170611d6d97
kustomize build ./kustomize-guestbook
```
