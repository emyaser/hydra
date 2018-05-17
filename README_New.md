# hydra

hydra是一个基于[go语言](https://github.com/golang/go "golang")、以快速便捷开发服务为目的的服务框架。你可以使用hydra快速开发包括http接口、web应用、RPC服务、流程服务、任务调度、消息消费(MQ Consumer)等多种服务，并且不必关注底层实现，仅仅着重于你的服务内容自身。通过简单的配置，即可启动并为用户提供服务。通过阅读快速入门，你将能快速创建并启动一个属于你的hydra服务。本文档将帮助你更好上手使用hydra来开发你的服务，并且也会对hydra的各个功能细节进行介绍。

## hydra使用

1. [快速入门](https://github.com/micro-plat/hydra/blob/master/manual/quickstart/1.hydra_install.md)
    * [安装hydra](https://github.com/micro-plat/hydra/blob/master/manual/quickstart/1.hydra_install.md)
    * [你的第一个hydra项目](https://github.com/micro-plat/hydra/blob/master/manual/quickstart/2.first_project.md)
2. [hydra介绍](https://github.com/micro-plat/hydra/blob/master/manual/quickstart/2.dependency_install.md)
    * [详细介绍](https://github.com/micro-plat/hydra/blob/master/manual/quickstart/2.dependency_install.md)
    * [其他依赖组件](https://github.com/micro-plat/hydra/blob/master/manual/quickstart/2.dependency_install.md)
3. hydra服务器
    * api服务器
    * web服务器
    * rpc服务器
    * mq consumer
    * 定时任务服务器(cron)
4. hydra日志组件
5. 系统监控与报警
6. 服务治理

## hydra架构

1. 框架结构
    * Context
    * Response
2. 服务器运行过程
3. 请求处理过程

## 其它延伸阅读内容

1. 注册中心