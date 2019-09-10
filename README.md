### 步骤一：创建项目
1.选择 Spring Cloud Routing 中的 Gateway

### 步骤二：
1. 配置 src/main/resources/application.yml
2. 访问 http://localhost:8080/spring-cloud ，会自动转发到配置的网址

### 注意点
1. 本机 IP = 10.98.164.127, 当使用远程地址断言的时候, 只有 http://10.98.164.127:9030 的才能匹配, 而 http://localhost:9030 或者 http://127.0.0
.1:9030 都是匹配不上的。（出处：http://antsnote.club/2019/05/20/Spring-SpringCloud%E4%B9%8BGateWay%E5%85%A5%E9%97%A8%E5%92%8CPredicate/ ）

### 参考
参考资料 | 网址
--- | ---
springcloud(十五)：服务网关 Spring Cloud GateWay 入门 | http://www.ityouknow.com/springcloud/2018/12/12/spring-cloud-gateway-start.html
