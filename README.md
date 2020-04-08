# helm-chart
helm的chart仓库地址为：https://yushanjin.github.io/helm-chart

1、添加chart仓库
```
helm repo add myrepo https://yushanjin.github.io/helm-chart
```
2、添加成功
```
helm repo list
NAME  	URL                                   
myrepo	https://yushanjin.github.io/helm-chart
```
3、搜索chart包
```helm search repo
NAME       	CHART VERSION	APP VERSION	DESCRIPTION                
myrepo/test	0.1.0        	1.16.0     	A Helm chart for Kubernetes
4、安装chart包
```
 helm install xxx myrepo/test
```
