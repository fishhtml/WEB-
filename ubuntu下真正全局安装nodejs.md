**简单思路**
 1. 去官网下载nodeJs已经编译好的压缩文件
 2. 解压文件到喜欢的目录
 3. 设置环境变量到`"目录/bin"`
 **对3说明**，如其中一种方法：
 新建node.sh文件，写入
`
 PATH="$PATH:/home/loo/myapp/node-v8.0.0-linux-x64/bin" 
export PATH 
`
其中`/home/loo/myapp/node-v8.0.0-linux-x64/`是我的nodeJs安装目录
重启，ok
