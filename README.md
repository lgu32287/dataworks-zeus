﻿Hadoop任务的调试运行到生产任务的周期调度
宙斯支持任务的整个生命周期

从功能上来说，支持：  
Hadoop MapReduce任务的调试运行  
Hive任务的调试运行  
Shell任务的运行    
Hive元数据的可视化查询与数据预览  
Hadoop任务的自动调度  

V0.15修改内容：
	1. 修改邮件发送bug,增加多个邮件发送人
	2. 修改Job自动开启关闭功能
	3. Noc报警配置写到配置文件
	4. JOB文件夹增加写的权限
v0.15.1
	增加自动开启关闭依赖检测。下游依赖存在开启，任务不能关闭。上游依赖全部开启，任务才能开启。
	从界面上移除了周期调度
	增加了历史action从内存中清除，并在数据库中备份，默认设置为两个月前的
v0.16修改漏跑程序


