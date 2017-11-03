sql：
	tableFrame:数据库表 ，优先执行
	initData：数据库必要表的一些初始数据，其次执行
	testData：示例接口的配置数据，最后执行。
settings.xml:
	maven仓库的具体配置文件
平台部署说明：
	平台开发、测试、生产环境的一些配置更改，及开发环境搭建的必要操作。
平台相关文档：
	crmpfcore、crmpfesb、crmpfmq、crmpftask的一些介绍。

MQ:
	topic、consumer 的创建命令详见mq脚本.txt，在生产环境执行时需注意修改ip、端口、cluster名称