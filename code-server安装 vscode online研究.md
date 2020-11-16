## vscode online 
为了方便在线开发，有时候需要执行一些简单的脚本

## 教程
https://blog.csdn.net/wnw001/article/details/106591047

## 实现
### docker 命令
docker run  --name vscode-online -u root -p 8086:8080 -v /data/my-code:/app/vscode-online/project -e PASSWORD=ShCzJ0lo2xdsvE3v codercom/code-server:latest --auth password


#### 参数
```
-u: 用户名
-v: 数据卷
-e: 环境变量（这里password明文了...期待有缘人吧）
```


#### 结果
成功实现 感觉蛮好用的