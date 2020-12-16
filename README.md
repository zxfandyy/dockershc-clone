# dockershc-clone
#克隆Az项目备份

使用shc简单隐藏Dockerfile安装运行的服务，以绕过pass平台封锁，变量SHURL脚本内容决定安装运行的服务

使用方式:

fork项目后重命名，修改Dockerfile文件中ENV SHURL ******地址为需要部署服务的脚本地址后部署服务端
可尝试选择main以外的diypb|ssraw|flyraw分支部署
客户端使用简要
TIPS:

如需部署到heroku推荐使用可定制性更强的这个项目
部署v3ray|55|br00k|g0st等脚本范例参考,可按需修改password|uuid|path等参数
某些pass平台会检测项目下所有文件和内容的关键字，请勿将部署脚本置于同项目下，欢迎PR有趣的脚本到上面across项目下的dockershc目录
