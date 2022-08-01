# tekton-gatling-pipeline.yaml


```
kubectl apply -f https://github.com/making/tekton-gatling-pipeline/raw/main/pipeline.yaml
tkn pipeline start gatling-test -p target_url=https://example.com -p duration=10s -p requests=100 --showlog
tkn pipeline delete gatling-test -n playground -f
```
