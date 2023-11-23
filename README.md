# Usage

### Copy paste this message into your terraform root folder/file
```
module "namespace" {
  source = "nadiaconeaev89/namespace/kubernetes"
  name   = "test"
  labels = {
    environment = "dev"
  }
  annotations = {
    managed_by = "terraform"
  }
}
```