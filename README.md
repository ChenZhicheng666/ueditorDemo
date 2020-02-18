# ueditorDemo
Ueditor前后端代码（springboot+vue）,

后端部分图片上传为本机测试，保存图片位置是项目外部地址E:/myServer（本机tomcat的映射路径），对应访问图片的前缀为localhost:8080,
请根据需要修改config.json及相关代码

后端占用端口8081（调用http://127.0.0.1:8081/ueditor/exec?action=config，返回配置文件的json即配置成功），
前端ueditor.config.js下服务器统一请求接口路径serverUrl: "http://localhost:8081/ueditor/exec"


##前端vue项目
安装依赖
npm install
运行
npm run dev
