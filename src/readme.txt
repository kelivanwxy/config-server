1、添加Spring Cloud Config中Config Server
2、启动类添加注解@EnableConfigServer
3、配置yml
    spring:
      cloud:
        config:
          server:
            git:
              uri: https://github.com/kelivanwxy/config-repo