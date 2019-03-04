# lcn-transferAccount-demo
springCloud转账demo 基于tx-lcn框架的分布式事物

1. 注册中心用的是consul,而不是Eureka 
2. 首先启动txlcn-tm模块,修改mysql redis配置文件,然后执行 java -jar txlcn-tm-5.0.1.RELEASE.jar 
3. 接着再启动两个项目 
