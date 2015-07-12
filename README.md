# Django1.8.4-CN-documentation-translation
**Django1.8中文文档翻译**

##项目介绍

此项目希望能将Django1.8的英文文档翻译成中文文档，为国内的开发者使用。

本人英语能力有限，时间也不是很多，有愿意一起翻译的可以联系，分章节完成。

- `en-pdf`为官方的Django1.8.4版本的PDF文档
- `zh-docs`为翻译的中文文档
##当前阶段
第一章翻译完成，没有做链接
##如何开展工作
有些朋友可能不太清楚如何帮忙翻译，我这里写一个简单的流程，大家可以参考一下：

1. 首先fork这个项目
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 在命令行运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/Tuluobo/Django1.8.4-CN-documentation-translation.git` 把我的库添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream master` 拉取我的库的更新到本地
8. 运行 `git rebase upstream/master` 将我的更新合并到你的分支

这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。

如果修改过程中我的库有了更新，请重复6、7、8步。

修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 pull request 按钮，点击它，填写一些说明信息，然后提交即可。
（以上方法步骤摘录[numbbbbb](https://github.com/numbbbbb)的项目中，在此感谢。）

##译者记录和翻译进度


- 目录（[Tuluobo](http://https://github.com/Tuluobo)）
- 第一章 Djang文档（[Tuluobo](http://https://github.com/Tuluobo)）
- 第二章
    + 2.1 Django一瞥
	+ 2.2 快速安装指南
	+ 2.3 编写自己的第一个Django App（1）
	+ 2.4 编写自己的第一个Django App（2）
	+ 2.5 编写自己的第一个Django App（3）
	+ 2.6 编写自己的第一个Django App（4）
	+ 2.7 编写自己的第一个Django App（5）
	+ 2.8 编写自己的第一个Django App（6）
	+ 2.9 高级教程：如何编写可重用的Apps
	+ 2.10 延伸阅读
	+ 2.11 编写你的第一个Django补丁
- 第三章 Django使用

	+ 3.1 如何安装Django
	+ 3.2 模型和数据库
	+ 3.3 处理HTTP请求
	+ 3.4 使用表单
	+ 3.5 模板
	+ 3.6 基类视图
	+ 3.7 数据库迁移
	+ 3.8 文件管理
	+ 3.9 Django中的测试
	+ 3.10 在Django中使用认证
	+ 3.11 Django的缓存框架
	+ 3.12 条件视图处理
	+ 3.13 加密签名
	+ 3.14 发送邮件
	+ 3.15 国际化和本地化
	+ 3.16 “local flavor”插件
	+ 3.17 日志
	+ 3.18 分页
	+ 3.19 移植到Python3
	+ 3.20 Django中的安全
	+ 3.21 性能优化
	+ 3.22 序列化Django对象
	+ 3.23 Django设置项
	+ 3.24 信号量
	+ 3.25 系统校验框架
- 第四章 “How-to”指南

	+ 4.1 使用	`REMOTE_USER`进行身份认证
	+ 4.2 编写自定义的django-admin命令  
	+ 4.3 编写自定义的模型字段 
	+ 4.4 自定义查找
	+ 4.5 自定义模板标签和过滤器 
	+ 4.6 编写自定义存储系统 
	+ 4.7 部署Django 
	+ 4.8 升级Django到一个更新的版本 
	+ 4.9 错误报告 
	+ 4.10 为模型提供初始化数据 
	+ 4.11 在Jython上运行Django 
	+ 4.12 Django与传统数据库的集成  
	+ 4.13 用Django输出CSV 
	+ 4.14 用Django输出PDF
	+ 4.15 管理静态文件(CSS, images)
	+ 4.16 部署静态文件 
	+ 4.17 如何在Windows安装Django
	+ 4.18 编写数据库迁移
- 第五章 Django FAQ

	+ 5.1 FAQ: 通用的常见问题
	+ 5.2 FAQ: 安装常见问题
	+ 5.3 FAQ: Django使用
	+ 5.4 FAQ: 获得帮助
	+ 5.5 FAQ: 数据库和模型
	+ 5.6 FAQ: 后台管理
	+ 5.7 FAQ: 贡献代码
	+ 5.8 发现错误
- 第六章 API参考

	+ 6.1 应用App
	+ 6.2 系统校验框架
	+ 6.3 内置的基类视图API
	+ 6.4 点击劫持保护
	+ 6.5 `contrib`包
	+ 6.6 跨站请求伪造保护
	+ 6.7 数据库
	+ 6.8 `django-admin`和`manage.py`
	+ 6.9 在你的代码中运行管理命令
	+ 6.10 Django异常
	+ 6.11 文件处理
	+ 6.12 表单
	+ 6.13 中间件
	+ 6.14 数据库迁移操作
	+ 6.15 模型
	+ 6.16 `Request`和`response`对象
	+ 6.17 `SchemaEditor` 
	+ 6.18 设置项
	+ 6.19 信号量
	+ 6.20 模板
	+ 6.21 `TemplateResponse`和`SimpleTemplateResponse`
	+ 6.22 Unicode数据
	+ 6.23 `django.core.urlresolvers`实用方法
	+ 6.24 `django.conf.urls`使用方法
	+ 6.25 Django工具类
	+ 6.26 验证器
	+ 6.27 内置视图
- 第七章 元文档和杂录

	+ 7.1 API稳定性
	+ 7.2 设计原则
	+ 7.3 Django的第三方分支
- 第八章 术语表

- 第九章 发行说明

	9.1 最新发行版
	9.2 安全发行版
10 Django内部信息

	+ 10.1 为Django贡献代码
	+ 10.2 邮件列表
	+ 10.3 Django项目的组织
	+ 10.4 Django团队
	+ 10.5 角色
	+ 10.6 Django的安全策略
	+ 10.7 Django发行过程
	+ 10.8 Django弃用时间表
	+ 10.9 Django源代码库
	+ 10.10 Django是如何形成的? 

- 第十一章 索引，术语和表格

- Python模块索引