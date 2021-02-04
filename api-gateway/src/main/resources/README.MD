#教程地址：
https://juejin.cn/post/6844903982599684103#heading-27
#依赖服务：
1.eureka-server
2.user-service
2.api-gateway
#注意事项：
1.不同的场景看文档中 需要修改配置文件 以及pom 以及启动环境 以及clean项目
2.注意pom文件中，不同情况整合需要打开注释，如测试整合eureka时候 pom中需打开对eureka的注释 同时clean complie项目
3.用bootstrap.properties中来切换配置文件,dev是之前的application.yml
