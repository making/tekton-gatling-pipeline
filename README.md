# tekton-gatling-pipeline.yaml


```
kubectl apply -f pipeline.yaml
tkn pipeline start gatling-test -p target_url=https://example.com -p duration=10s -p requests=100 --showlog
tkn pipeline delete gatling-test -n playground -f
```
