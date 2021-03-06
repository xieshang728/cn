
# 创建仓库认证信息

**操作说明**

创建容器时如需要使用第三方镜像仓库的镜像，您需要先将第三方镜像仓库相关信息添加到仓库认证信息；

您保存到京东云的认证信息将会被妥善加密保存，用于下载第三方镜像仓库中指定的镜像；

仓库认证信息将在创建容器时被引用，详情参考创建容器实例帮助中心；

请及时将第三方镜像仓库的任何更新添加到京东云，以免容器实例下载镜像失败；

**操作指南**

1、打开京东云控制台，选择【弹性计算】-【容器服务】-【镜像仓库认证信息】进入仓库认证信息列表页；

2、点击列表页上的【创建仓库认证信息】按钮，打开仓库认证信息创建页面；

3、输入名称、第三方镜像仓库服务器地址、仓库用户名和密码后，邮箱为可选项，勾选页面上的授权说明，点击确定，将第三方镜像仓库相关信息添加到仓库认证信息。使用在Docker Hub创建的私有镜像，添加第三方仓库认证时，仓库域名建议该地址：https://index.docker.io      

注意：京东云使用https协议对镜像仓库相关信息进行加密传输，因此请在仓库域名前添加https:\\前缀；
