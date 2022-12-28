# **helm-charts**

helm的仓库地址为：https://yybht155.github.io/helm-charts

<hr>
<br>

- 添加chart仓库
```shell
helm repo add ghrepo https://yybht155.github.io/helm-charts
```

- 添加成功
```
helm repo list
```

- 搜索chart包
```
helm search []
```

- 安装chart包
```
helm install []
```

<hr>
<br>

- helm打包
```
helm package []
```

- 添加index
```
helm repo index --url https://yybht155.github.io/helm-charts .
```