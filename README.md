### Kustomization

### Install Kustomization

```shell
 $ brew install kustomize
```

### ArgoCD


### Mirror-Maker2

- generating yaml for local environment
    ```shell
      $ cd mirror-maker2/overlays/local
      $ kubectl kustomize ./ > mirror-maker2.yaml
    ```
- deploy Mirror-Maker2
  ```shell
    $ kubectl apply -f mirror-maker2.yaml
  ```
