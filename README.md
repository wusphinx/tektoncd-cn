# tektoncd-cn

由于`gcr.io`的镜像拉取不下来，而`tektoncd`的诸多镜像均依赖于`gcr.io`，所以做了一个体力活，将依赖镜像通过`github`的`action`转移到阿里云的镜像中心，
目前`tektoncd`版本为`v0.18.1`。