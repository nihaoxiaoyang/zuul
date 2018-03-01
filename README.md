# Micro service
基于spring cloud的分布式系统微服务的一次请求的生命周期

1）请求用任意方发起过api形式访问微服务域名
2）通过zuul集群（路由转发和过滤器）
3）通过ribbon+Hystrix（负载均衡和断路器）
4）分发服务集群的单个服务器
5）finnish