# Myplaybook
## 初始化步骤
1. 实现多主机间免密登录
   > #生成密钥
   > ssh-keygen -t rsa -f /root/.ssh/id_rsa -N ''
   > #实现密钥同步
   > ssh-copy-id 远程主机名称

2. 