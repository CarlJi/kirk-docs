# 3.8 配置中心

## 3.8.1 添加/删除 配置集

**配置集** 能够统一管理相关配置项，例如配置集可以是服务名，配置项为服务相关的环境变量值。

![](_figures/user-guide/configmap-create.gif)

## 3.8.2 添加/删除 配置项</span>

**配置项** 可以在多个服务之间进行复用，非常便于统一设置/修改，也避免了手动输入带来的出错风险。

![](_figures/user-guide/configmap-items.gif)

## 3.8.3 使用配置项

**配置项** 用于便捷设置服务内 **环境变量的变量值**。

**操作如下：**  
1. 添加服务时，选择加载方式为 **配置中心**  
2. 选择对应的配置集，如图 **"wordpress-db"**  
3. 选择对应的配置项，如图 **"db-password"**

![](_figures/user-guide/configmap-add-item.png)