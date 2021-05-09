### 简述 kubectl log / describe / apply / delete 命令的功能
log: 查看日志
describe: 描述资源信息
apply: 应用配置文件
delete: 删除资源

### 简单描述 Pod, Node, Deployment, Service, Ingress, ReplicaSet, Namespace 概念
Pod：最小调度单元,多个容器集合，共享namespace
Node: 业务节点,
Deployment: 声明式更新控制器，用于发布无状态应用
Service: 服务,将一组pod关联起立，提供一个统一的入口
Ingress: 负载均衡
ReplicaSet: 副本
Namespace: 命名空间，隔离资源

### kubernetes cronjob
周期性作业任务

### scale
kubectl scale --replicas=3 deployment/myapp -n default 