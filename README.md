# vault-unsealer-operator
Kubernetes deployment.

vault-key-secret.yml
```yaml
 apiVersion: v1
 kind: Secret
 metadata:
   name: thresholdkeys
 type: Opaque
 stringData:
   key1: xxx
   key2: xxx
   key3: xxx
 ```
