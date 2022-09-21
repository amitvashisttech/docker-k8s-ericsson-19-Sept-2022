```
304  cd 05-Service/
  305  ls
  306  kubectl  get pods
  307  kubectl  delete -f helloworld-rc.yaml
  308  ls
  309  kubectl  get pods
  310  ls
  311  kubectl  get pods -o wide
  312  kubectl  apply -f helloworld-rc.yaml
  313  kubectl  get pods -o wide
  314  kubectl  delete pod helloworld-controller-4ptvr helloworld-controller-n6dq4
  315  kubectl  get pods -o wide
  316  kubectl  expose pod hello-k8s --type=NodePort
  317  kubectl  get pods -o wide
  318  kubectl  get svc
  319  kubectl  expose rc helloworld-controller --type=NodePort
  320  kubectl  get svc
  321  cat helloworld-rc.yaml
  322  kubectl  get svc
  323  kubectl  describe svc helloworld-controller
  324  kubectl  get pods -o wide
  325  kubectl  delete pod helloworld-controller-6frkl
  326  kubectl  get pods -o wide
  327  kubectl  describe svc helloworld-controller
  328  kubectl  get pods --show-labels
  329  kubectl  scale --replicas=1 rc helloworld-controller
  330  kubectl  describe svc helloworld-controller
  331  kubectl  get pods --show-labels
  332  kubectl  get pods -o wide
  333  kubectl  scale --replicas=2 rc helloworld-controller
  334  kubectl  get pods -o wide
  335  kubectl  describe svc helloworld-controller
  336  ls
  337  history
  338  kubectl  get svc
  339  kubectl  delete svc helloworld-controller
  340  kubectl  delete svc hello-k8s
```
