# SpringBoot Template <img style="float:right;width:100px;padding-top:35px" src="https://img.shields.io/npm/l/vux.svg?style=flat-square" alt="">
> 在ise实验室工作了8个月，一直想整理一套理想的后端即clone即用的模版。这套SpringBoot的模版也在不断的完善当中，从初始的简单框架逐渐加入了更多的管理和运维工具。

## Dependencies
- [【Server】SpringBoot](http://projects.spring.io/spring-boot/)
- [【Database】Mysql](https://www.mysql.com/)
- [【Testing】Mockito](http://site.mockito.org/)
- [【API Management】Swagger2](http://swagger.io/)
- [【Code Quality】Sonar](https://www.sonarqube.org/)

## Features
1. 请求接收，逻辑转发，对象映射，hibernate数据读写等主流功能
1. 微服务标准分包结构
1. 具体的使用样例，以示例代码的形式展示
1. 详细的单元测试，接口测试
1. Swagger2 HTTP API管理
![swagger](http://mooctest.oss-cn-shanghai.aliyuncs.com/resources/springboot-tmpl/swagger.png)

1. Sonar代码质量监测
![sonar management](http://mooctest.oss-cn-shanghai.aliyuncs.com/resources/springboot-tmpl/sonar-management.png)
![sonar map](http://mooctest.oss-cn-shanghai.aliyuncs.com/resources/springboot-tmpl/sonar-map.png)

## Configurations
- 创建sample数据库，或者在resources/application.yaml文件中修改数据库名称以及登录用户名和密码
- 下载Sonar本地服务器，由于是依赖Maven进行Sonar质量检测，请在./m2/settings.xml中进行Sonar的相关配置

## Keep In Touch
- 欢迎clone/fork/star!
- 欢迎在issue中讨论
- 欢迎访问个人网站www.alandelip.cn