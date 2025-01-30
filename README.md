# flew-index

## fl(avono123's custom kr)ew index

### Install

```sh
k krew index add flew https://github.com/flavono123/flew-index.git
```

### Plugins

- [pickdeep(kupid)](https://github.com/flavono123/kupids)
- [eks-node](https://github.com/flavono123/kubectl-eks-node)
- [view-lables](https://github.com/flavono123/kubectl-view-labels)

### Test in Local

- [Krew Doc: Testing plugin installation locally](https://krew.sigs.k8s.io/docs/developer-guide/testing-locally/)

```sh
k krew uninstall <plugin>
k krew install --manifest plugins/<plugin>.yaml
```
