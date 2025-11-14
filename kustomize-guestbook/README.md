# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/pbhatnagar-oss/argocd-example-apps
# cd into the cloned directory
git checkout 06b42aaec87ed650571a6aedb94e48a374159b06
kustomize build ./kustomize-guestbook
```
