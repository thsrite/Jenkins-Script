# Jenkins-Script
Jenkins 自动化部署回滚脚本

auto_build.sh：部署脚本

auto_destroy.sh：清理脚本

auto_rollback.sh：回滚脚本

Dockerfile-java/vue：docker打包

gitlab_token.sh：获取gitlabtoken，这里用不到

isExitFile.sh：校验文件是否存在，这里用不到

sendmail.sh：发送邮件

easy_ci.sh：启动脚本

参数如下：

  #-g 项目的git地址

  #-p docker容器运行的端口映射关系

  #-l 项目的语言：java or vue

  #-m 接收邮件的邮箱

  #-h help

  #-d docker私服配置

  #-e easy-ci脚本路径

  #-s 日志地址配置

  #-w 项目存放地址配置

  #-n 项目日志名称

  #-i 是否本地部署

  #-u 远程用户名

  #-r 远程密码
