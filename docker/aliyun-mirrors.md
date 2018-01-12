## 阿里云docker镜像加速

第一步：访问[阿里云镜像地址](https://dev.aliyun.com/search.html)

第二步：使用自己帐号登录阿里云

第三步：进入到[管理中心](https://cr.console.aliyun.com/)

第四步：点击[镜像加速器](https://cr.console.aliyun.com/#/accelerator)

第五步：删除默认的虚拟机

`docker-machine ls` 查看是否有默认的虚拟机

`docker-machine rm default` 删除name为default的默认虚拟机

第六步：按照对应的环境配置
