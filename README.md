# spring-quartz
spring与quartz结合使用，集群配置
# 运行环境
1. 数据库：mysql 5.7.18 
2. 操作系统：centos7,vmware配置集群
3. tomcat8
4. quartz版本：2.2.1
# 运行步骤
1. 下载源码，导入eclipse
2. 运行tables_mysql_innodb.sql,建立数据库;运行create-schema.sql,建立作业表
3. 将项目打成war包,分布部署在不同的机器上的tomcat中,运行tomcat,访问网页网址建立调度作业,这里建立的调度作业只是简单的输出作业信息,注意修改数据库连接配置
4. 在tomcat下logs文件夹下的catalina.out文件中可以看到输出的结果

