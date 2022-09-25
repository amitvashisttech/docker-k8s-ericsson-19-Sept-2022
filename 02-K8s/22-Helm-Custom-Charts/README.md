```
923  mkdir 22-Helm-Custom-Charts
  924  cd 22-Helm-Custom-Charts/
  925  ls
  926  helm create my-tiny-web
  927  ls
  928  cd my-tiny-web/
  929  ls
  930  ls -ltr
  931  cd charts/
  932  ls
  933  cd ..
  934  ls
  935  cat Chart.yaml
  936  ls
  937  ls -ltr templates/
  938  ls -ltr templates/service.yaml
  939  cat templates/service.yaml
  940  s
  941  ls
  942  vim values.yaml
  943  ls
  944  cd ..
  945  ls
  946  helm install my-app-1 my-tiny-web --dry-run
  947  vim my-tiny-web/values.yaml
  948  helm install my-app-1 my-tiny-web --dry-run
  949  vim my-tiny-web/values.yaml
  950  helm install my-app-1 my-tiny-web --dry-run
  951  vim my-tiny-web/values.yaml
  952  helm install my-app-1 my-tiny-web --dry-run
  953  helm install my-app-1 my-tiny-web
  954  helm list
  955  kubectl  get deploy
  956  kubectl  get pods
  957  kubectl  get rs
  958  kubectl  rollout history deploy my-app-1-my-tiny-web
  959* kubectl  rollout history deploy my-app-1-my-tiny-web --revision=
  960  kubectl  rollout history deploy my-app-1-my-tiny-web --revision=2
  961  kubectl  rollout history deploy my-app-1-my-tiny-web
```
