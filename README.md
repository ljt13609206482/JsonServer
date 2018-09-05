# JsonServer
这是一个使用jsonServer 搭建的一个获取测试数据的虚拟服务器，数据存放在db.json文件中，可以根据自己的需要自定义。
下面我将意义列举实现步骤；
备注：本人使用的编辑器是VSCode;


第一步，打开终端，在根路径下全局安装json-server，命令是：npm install -g json-server，

第二步，创建一个文件夹，在终端打开该文件夹路径；

第三步，初始化一个package.json文件，也就是在终端输入一个命令：npm init;

第五步，安装一个json-server模块，命令：npm install json-server --save

第六步，调整一下package.json的启动命令，"json-server":"josn-server --watch db.json"

第七步，创建一个db.json文件，编写自己所需的数据；

第八步，启动一下jsonserver，命令：npm run json-server;


jsonServer服务器启动之后，会在终端中显示访问地址，可以根据自己的需求访问；
以上就是全部搭建jsonServer虚拟服务器的步骤
