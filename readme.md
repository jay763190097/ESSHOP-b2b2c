# ESSHOP

## 部署

1. 修改jdbc.properties文件的数据库地址
2. 修改persistence.xml 
3. 启动服务

jdk1.7下运行

```xml
<property name="hibernate.hbm2ddl.auto" value="create"/>
```
第一次启动改为create

删除webapp下的install.lock
可以使用tomcat启动服务
然后进入地址localhost:8080/contextPath/install.htm

输入后台管理员账号密码，等待安装完成。
admin/123456

效果图
![image](./images/20191109121825.png)

管理后台

![image](./images/深度截图_选择区域_20191115223408.png)
![image](./images/深度截图_选择区域_20191115225607.png)
![image](./images/深度截图_选择区域_20191115225631.png)

