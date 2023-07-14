# helm-chart

## helm的chart仓库地址为：https://yandongxiao.github.io/helm-chart-demo

## 本Chart仓库的使用方法

1、添加chart仓库
```
helm repo add myrepo https://yandongxiao.github.io/helm-chart-demo
```

2、安装chart包
```
helm install xxx myrepo/test
```

xxx为relaese名字

3、将该 helm chart 发布到 artifacthub.io 上。作为 Verified Publisher，需要添加`arrifacthub-repo.yaml`文件到仓库根目录。

