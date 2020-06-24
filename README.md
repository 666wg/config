一、命名规则（分支、文件名称）：  
/{label}/{application}-{profile}.properties|yml

二、下面我们详细介绍上面参数的含义：  
① label ：远程仓库的分支名字。如果我没有指定该参数默认按照master访问，即在访问时，如果分支为master可以省略。  
② application ：为该应用在Eruke注册中心的ID，即spring.application.name的名称。  
③ profile ：不同环境的名字。例如:dev(开发环境)、test(测试环境)、prod(生产环境)等。  

三、访问示例：  
http://localhost:8081/master/springcloud-client-prod.yml   
说明：端口号为配置中心微服务工程的端口号，非客户端微服务工程的端口号
