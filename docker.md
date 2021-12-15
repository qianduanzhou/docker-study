# docker学习

## 相关文档

[菜鸟教程]: https://www.runoob.com/docker/docker-tutorial.html	"菜鸟教程"
[官网]: https://www.docker.com/get-started	"官网"

## vue3部署

1. 先执行npm run build打包
2. 创建一个Dockerfile文件，写入docker相关配置
3. 通过Dockerfile生成container

## mysql部署

参考菜鸟教程，记得创建对应数据库

[docker-mysql]: https://www.runoob.com/docker/docker-install-mysql.html	"创建mysql映像及容器"

## beego部署

1. 先执行bee pack -be GOOS=linux
2. 创建一个Dockerfile文件，写入docker相关配置
3. 与mysql关联，通过network创建一个公用网络
4. 通过Dockerfile生成同个network下的container