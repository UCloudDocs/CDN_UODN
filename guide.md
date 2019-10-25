# 使用指南



## 运营商资源

UODN控制台提供全局［带宽监控］功能，区分：一线城市单线带宽、二线城市单线带宽、全国教育网

![](/images/odn_umon.jpeg)

## 节点资源

UODN产品目前处于内测阶段，内测用户UCloud会帮客户完成节点资源创建。

## 容器资源

UODN产品目前处于内测阶段，内测用户目前支持在控制台对容器资源的开启、关闭、重启、重装镜像功能。

### 开启容器

![](/images/odn_docker.jpeg)

### 关闭容器

![](/images/odn_docker.jpeg)

### 重启容器

![](/images/odn_docker.jpeg)

### 更新镜像

![odn\_docker.jpeg]

1.镜像库（UHub）

用户使用UHub产品上传Docker相关镜像到UCloud镜像库，可以选择任意版本镜像安装至ODN容器

![odn\_image\_hub.jpeg]

2.其他地址

用户可以提供第三方镜像库中的镜像URL，安装至ODN容器。但必须是公共的，无权限限制的地址

镜像填写范例：uhub.service.ucloud.cn/{已创建镜像仓库}/{镜像}:tag

![odn\_image\_diy.jpeg]
