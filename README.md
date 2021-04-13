# 概览

* [新手引导](/uk8s/readme2)
* [产品简介](/uk8s/introduction/README)
    * [产品概念](/uk8s/introduction/whatisuk8s)
    * [使用须知](/uk8s/introduction/restriction)
    * [名词解释](/uk8s/introduction/concept)
    * [漏洞修复记录](/uk8s/introduction/vulnerability/README)
    * [集群节点配置推荐](/uk8s/introduction/node_requirements)
    * [kube-proxy模式选择](/uk8s/introduction/kubeproxy_mode)
* [产品价格](/uk8s/price)
* [操作指南](/uk8s/userguide/README)
    * [使用必读](/uk8s/userguide/before_start)
    * [创建集群](/uk8s/userguide/createcluster)
    * [删除集群](/uk8s/userguide/deletecluster)
    * [查看集群](/uk8s/userguide/describecluster)
    * [添加节点](/uk8s/userguide/addnode)
    * [kube-proxy模式切换](/uk8s/userguide/kubeproxy_edit)
* [使用kubectl操作集群](/uk8s/manageviakubectl/README)
    * [kubectl命令行简介](/uk8s/manageviakubectl/intro_of_kubectl)
    * [安装及配置kubectl](/uk8s/manageviakubectl/connectviakubectl)
    * [使用web kubectl](/uk8s/manageviakubectl/webterminal)
    * [集群更新凭证](/uk8s/manageviakubectl/reset_token)
    * [创建PVC](/uk8s/manageviakubectl/createpvc)
    * [创建Service](/uk8s/manageviakubectl/createservice)
* [存储卷](/uk8s/volume/README)
    * [CSI 升级](/uk8s/volume/CSI_update)
    * [Volume 介绍](/uk8s/volume/intro)
    * [在UK8S中使用UDISK](/uk8s/volume/udisk)
    * [在UK8S中使用已有UDISK](/uk8s/volume/statusudisk)
    * [在UK8S中使用UFS](/uk8s/volume/ufs)
    * [动态PV使用UFS](/uk8s/volume/dynamic_ufs)
    * [在UK8S中使用US3](/uk8s/volume/ufile)
* [服务发现](/uk8s/service/README)
    * [Service 介绍](/uk8s/service/intro)
    * [通过内网ULB访问Service](/uk8s/service/internalservice)
    * [通过外网ULB访问Service](/uk8s/service/externalservice)
    * [使用已有的ULB](/uk8s/service/ulb_designation)
    * [ULB参数说明](/uk8s/service/annotations)
    * [ULB属性修改的处理方法](/uk8s/service/change_ulb_name)
    * [获取真实客户端IP](/uk8s/service/getresourceip)
    * [通过ULB暴露Dashboard](/uk8s/service/dashboard)
    * [Ingress支持](/uk8s/service/ingress/README)
* [集群网络](/uk8s/network)  
* [网络隔离](/uk8s/networkpolicy)
* [应用商店](/uk8s/helm/README)
    * [关于应用商店](/uk8s/helm/abouthelm)
    * [安装使用应用商店](/uk8s/helm/init)
    * [安装应用](/uk8s/helm/install)
    * [管理应用](/uk8s/helm/manager)
    <!-- * [一键安装应用](/uk8s/helm/installapp) -->
* [日志管理](/uk8s/log/README)
    * [使用ELK自建UK8S日志解决方案](/uk8s/log/elastic_filebeat_kibana_solution)
    * [使用UK8S日志插件功能](/uk8s/log/ELKplugin)
* [监控管理](/uk8s/monitor/README.md)
    * [Prometheus监控方案](/uk8s/monitor/prometheus/README)
* [集群管理](/uk8s/administercluster/README)
    * [配置自定义DNS服务](/uk8s/administercluster/custom_dns_service)  
    * [ETCD备份](/uk8s/administercluster/etcd_backup)
    * [集群版本升级](/uk8s/administercluster/cluster_version_update)
    * [制作自定义镜像](/uk8s/administercluster/custom_image)
    * [自定义数据](/uk8s/administercluster/cloud_init)
    * [GPU共享插件](/uk8s/administercluster/gpu-share)
* [镜像仓库](/uk8s/dockerhub/README)  
    * [概述](/uk8s/dockerhub/outline)  
    * [在UK8S中使用UHub](/uk8s/dockerhub/using_uhub_in_uk8s)   
* [常见问题](/uk8s/q/README)
    * [集群常见问题](/uk8s/q/cluster)  
    * [镜像库常见问题](/uk8s/q/registry) 
    * [容器常见问题](/uk8s/q/container) 
    * [存储插件问题](/uk8s/q/storage)
* [排障指南](/uk8s/troubleshooting/README)
    * [入门必读](/uk8s/troubleshooting/startguide)
    * [镜像制作与容器常见问题](/uk8s/troubleshooting/k8s_debug_summary)
    * Pod 故障处理
        * [概述](/uk8s/troubleshooting/pod_debug_summary)
    * Node 故障处理
        * [概述](/uk8s/troubleshooting/node_debug_summary)
        * [预防OOM](/uk8s/troubleshooting/prevent_oom)
    * [集群ULB误删处理](/uk8s/troubleshooting/ulb_undelete)
* [最佳实践](/uk8s/bestpractice/README)
    * [基于Jenkins的CI/CD实践](/uk8s/bestpractice/cicd)
    * [权限管理](/uk8s/bestpractice/authorization/README)
    * [亲和性实践](/uk8s/bestpractice/affinity)
    * [Kubernetes弹性伸缩](/uk8s/bestpractice/autoscaling/README)
