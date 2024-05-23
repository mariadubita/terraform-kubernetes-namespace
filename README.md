# Usage

### Please copy paste below code 
```
module "testns" {
  source = "mariadubita/namespace/kubernetes"
  name   = "testns"
  annotations = {
    new = "application"
  }
  labels = {
    createdby = "mariadubita"
  }
}
```
