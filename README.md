# Usage

### Please copy paste below code 
```
module "testns" {
  source = "mariadubita/namespace/kubernetes"
  name             = "testns"
  pod_quota        = 50
  pod_cpu_limit    = "2096m"
  pod_memory_limit = "4Gi"
  annotations = {
    new = "application"
  }
  labels = {
    createdby = "mariadubita"
  }
}
```
