配置文件命名要求（文件命名与分支无关，不同环境配置文件可以放在不同分支）：
格式：clientId-profile.properties|yml
只有符合格式才可以被springcloud远程调用
clientId为该应用在Eruke注册中心的ID，即spring.application.name的名称
profile是指什么环境下的配置文件，例：dev（开发环境）、test（测试环境）、prod（生产环境）
