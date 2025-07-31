
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/stephenneweydl/argocd-example-apps
# cd into the cloned directory
git checkout 71541d014658ef1536872727a158b3db26bd36ea
helm template . --name-template staging-helm-guestbook --include-crds
```