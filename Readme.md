# study 进度 

chapter 1 identityserver 4 准备
chapter 2 docker 准备
chapter 3 用户服务
chapter 4 网关与认证
chapter 5 通讯录服务
chapter 6 项目|推荐 服务
chapter 7 微服务监控与部署


chapter 1
1-27  完成
	注： 需要重点回顾和理解 review and  comprehend the oath flow
chapter 2
28-51 完成 
	50 -51  为 GitLab Runner  注册 公网的 Gitlab server  以后需要时再学习
	注 dock network  互联部分可以稍微再回顾下
chapter 3 
52 -73    部分完成
	67-73 未完成 主要时  gitlab的 CI
	注 为 finbook 用例图的完整介绍 需要重点回顾和理解

chapter 4  网关与认证  部分完成
74-85
	80 82
	注  ocelot 集成Consul服务发现再理解，polly 的理解 

chapter 5 通讯录服务
86 - 105  初步完成 需要确认

chapter 6 项目|推荐 服务
106-132

	125-132 推荐服务实现
		实现步骤
		1 接收IntegrationEvent ,实现 Project create event hanlder
		2 创建recommand ef,通过ef context插入数据库
		3 写 recommend api controller ,get recommends by identity,即完成通过用户id 获取 项目推荐列表

	130-132 完成  
	121-123 dapper queries 需要再复习


chapter 7 微服务监控与部署	
133-
		大致过了一遍
		完成zipkin的安装, 但存在问题 完成elasticsearch安装 简单交互  具体见 readme.txt 2019年6月1日


需要记录的文档类型
	用例图
	泳道图
	架构
		单体，单体的演进，网关 ocelot+consul
	每个技术点的文档
		比如 consul,ocelot,identityserver4 单独的文档记录
	项目实战 的roadmap,  开发过程的记录， 每个章节的功能开发列表
		比如 	
			任务130： 推荐服务实现 - 访问联系人服务获取好友信息
				使用通讯录查找所有好友，给这些好友添加 推荐记录
			18:07 
			任务131： 推荐服务实现 - 调试推荐服务
			21:00 
			任务132： 推荐服务实现 - 推荐服务加入网关
	围绕架构图 试讲

资料
	项目用例图
		https://www.processon.com/diagraming/58ed81a1e4b0c9097c3d7c5c
	泳道图
		https://www.processon.com/apps/596466a9e4b0c5e101f479c4