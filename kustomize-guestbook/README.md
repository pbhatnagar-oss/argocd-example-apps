# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 6781d6b5d9ee54c0d23b085d795c7732d60cfcc0
kustomize build ./kustomize-guestbook
```
