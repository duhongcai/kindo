#Kindo Framework
自己根据常用框架而搭的“轮子”框架。希望借由造轮子能够加深java框架编程知识，完善自己。考虑加入的组件包括：kindo-io、kindo-web、kindo-jetty、kindo-sso、kindo-cache、kindo-rpc、kindo-sjdbc等，分别涉及到IO通信、MVC、单点登录、缓存等知识点。
***
## kindo-io 
基于NIO封装实现简单的socket通信框架，参照netty、mina等。
***
## kindo-web
基于servlet参照springmvc等常用web框架造的自己MVC轮子。通过此能深入了解springmvc框架中各个组成及实现原理逻辑。
***
## kindo-jetty
 参照jetty实现简易版web服务器。通过此深入了解类加载、HTTP解析等知识点。
***
## kindo-sso
 基于客户端cookie实现简易版单点登录框架，可以实现分布式集群管理。
***
## kindo-cache 
参照spring cache实现更贴合自身需要的轮子cache组件，实现方便的缓存使用，尽量做到对使用者不可感知，简化操作。
***
## kindo-rpc 
参照dubbo造轮子，实现基本rpc框架，包括服务注册、服务治理及监控等。
***
## kindo-sjdbc 
分库分表/读写分离的数据库统一分布式解决方案，并通过研究各种分布式事务解决方案封装一套自己的轮子解决方案，希望此过程加深对分布式事务解决方法的深入了解。此框架对外提供统一调用接口，封装内部分库分表逻辑，简化分布式环境下的数据库操作。
***
## 未完待续
