
FROM golang:latest
 
#创建工作目录
RUN mkdir -p /go/src/go_test/static/
 
#进入工作目录
WORKDIR /go/src/go_test
 
#将当前目录下的所有文件复制到指定位置
COPY dist/ /go/src/go_test
 
#端口
EXPOSE 8080
 
RUN chmod 777 ./beego_study
ENTRYPOINT ["./beego_study"]