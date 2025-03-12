1下载docker [
](https://www.docker.com/)
2 去dify github网站  参考官网
https://github.com/langgenius/dify
点击 code 选择 downld zip 文件
解压文件到 dify文件夹 这个随意 
在这个文件夹的地址栏 输入 cmd 进入终端
输入命令：docker compose up -d  进行安装
访问 127.0.0.1 进入dify 设置管理员 登陆后 点头像 进入设置
安装 ollama 模型 重启dify
进入设置 ollama模型  

名字输入：deepseek的全名（ollama list里面的）
地址（非常关键）：http://host.docker.internal:11434
添加成功 

参考：https://docs.dify.ai/development/models-integration/ollama