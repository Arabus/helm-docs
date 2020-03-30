special-characters
==================
A chart demonstrating handling of special characters in values files

Current chart version is `0.2.0`

Source code can be found [here](https://github.com/norwoodj/helm-docs/tree/master/example-charts/special-characters)



## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| elasticsearch.clusterHealthCheckParams | string | `"wait_for_status=yellow&timeout=1s"` | The Elasticsearch cluster health status params that will be used by readinessProbe command |
| elasticsearch.clusterHealthCheckParamsDescription | string | `""` | Now let's put some special characters in the description: wait_for_status=yellow&timeout=1s |
| htmlSnippets.one | string | `"<html>\n  <head></head>\n  <body>\n    <h1>Is this right, I don't know html</h1>\n  </body>\n</html>\n"` |  |
| htmlSnippets.three | string | `"<html><head></head></html>"` | Another description |
| htmlSnippets.two | string | `""` | Let's put it in the description <html></html> |