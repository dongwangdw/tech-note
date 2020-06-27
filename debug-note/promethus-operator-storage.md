# This is a interesting questions:

Please refer to [issue](https://github.com/coreos/prometheus-operator/issues/1897). In this issue, I found 
the prometheus name is `kube-prometheus`, the statefulset name is `prometheus-kube-prometheus`. And this prometheus is configured with PVC. The name of the used PVC is `prometheus-kube-prometheus-db-kube-prometheus-0`. And there is another PVC pending, whose name is `prometheus-kube-prometheus-db` 