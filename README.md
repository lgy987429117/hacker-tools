# hacker-tools
哈克工具 为了帮助你在制裁同学时可以使用的软件。
Python写的，Pyinstaller打包，目前360报木马，后续尝试解决。

现版本 Preview 1.0 是上周的半成品，被控端的保护进重启后无法自启动、只能在config.cfg中修改IP.....。这周（2025/03/29）打算更新1.0.

### 目前计划
1.0 修改Bug
1.01 加入中文.英文支持

### 目前破解方式
#### 1.0版本
### 1.以管理员身份结束保护进程svchost.exe，注意辨认。一般为任务管理器最上方或最下方（svchost中的）的一个svchost.exe（同内置svchost.exe一般无图标，不使用管理员权限会拒绝访问。默认存储路径为C:\Users\Administrator\AppData\Roaming）
### 2.结束client.exe（两个进程）。
### 3.删除C:\Users\Administrator\AppData\Roaming中的 svchost.exe 和 client.exe.
