# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout c598c49e9cdfff52a9dff3931963b408b0a3b0b1
kustomize build ./kustomize-guestbook
```
