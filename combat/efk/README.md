## EFK搭建
>参考博文：
>[阳明的博客 在kubernetes 上搭建EFK日志收集系统](https://www.qikqiak.com/post/install-efk-stack-on-k8s/) 
>[Kubernetes实战之部署ELK Stack收集平台日志](https://cloud.tencent.com/developer/article/1552277)
## 组件介绍
elasticsearch 博主本人使用集群分布式部署,replicas=3，由于我本地使用minikube,使用单个elasticsearch部署
## 注意
当前本地kubernetes使用minikube搭建，资源比较紧张，所以大部分组件都是单节点部署方式，