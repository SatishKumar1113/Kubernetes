# Kubernetes
---
apiversion: v1
kind: Pod
metadata: 
  name: alpine
spec:
  containers:
    -name: alpine
     image: alpinec
     args:
       -sleep
       -1d
