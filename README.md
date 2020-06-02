# 更多文档请前往docs目录查看

# laas-web

## 设计器

### 数据处理层

#### 元数据

##### 元数据管理

##### 元数据层级可视化及快速定位

#### 数据录入表单

多个层的表单需要联动

##### 前端层-数据录入表单

##### web层-数据录入表单

#### 数据操作DSL

其实就是业务层, 而且其实开发大部分花费的时间都是在这个上面

##### 操作元数据领域数据

##### 操作常规数据

##### 调用领域专属组件

##### 兼容历史项目

为了兼容历史项目

###### 历史项目分析组件

###### 历史项目编译器

###### 历史项目接入组件

###### 历史项目部署兼容组件

### 领域专属组件层

使用模板技术从标准版项目中抽取模板代码



#### 标准前端层

跟vue的component设计思路类似

#### 标准后台层

服务(springboot-web)

中间件

​	数据库

​	缓存

​	消息队列

第三方服务

#### 标准编译层

模型转译、DSL转译、 专属组件转译接入适配、部署状态适配、部署文件生成
A分析->B优化->C测试->D集成->E监控->A

#### 标准运行态层

以Dockerfile和Docker容器编排或者ansible playbook文件为典型例子, 需要注意的是持续部署, 然后这一块通常是配合工单使用

## 分发库

存储、拉取 已设计代码

## 执行引擎

加载并运行 运行层

# 期望值

业务人员只需要关注企业业务数据流转, 极大提高效率



甚至于, 如果专门去培养 产品开发 来使用这个项目开发项目, 好处之多简直不敢想象



技术和业务的发展形成一个正向循环



# 如何落地

## 开发顺序

分析->开发->测试->接入

### 1、开发 业务数据模型 设计器

### 1、开发领域专属组件-web

多技术和实际需要分析及接入, 抽象技术层去支撑多业务层, 构思抽取技术模板(前、后端), 一步式接入





### 2、开发 编译器-web 以及 历史兼容组件-项目代码生成器

### 3、鼓励业务开发人员去了解、学习、尝试使用、反馈建议/意见

### 4、开发分发库

### 5、完善历史兼容组件: 项目代码生成器、历史项目部署兼容组件、历史项目分析、历史项目接入器

### 6、完善领域专属组件: 前端层、web层、运行层

## 推动点

自上而下构建信任观, 形成交付观, 明确需求和实际完成度

否定工时之类的绩效方式, 重新定义绩效方式, 以结果导向(OKR), 在使用更高效率的技术之后, 结果更好, 绩效更高, 形成正向循环

以原有绩效的0.7~0.9为原点绩效, 绩效与薪资关联

休息时间拉长, 让员工的工作更加富有效率, 形成正向循环



公司需要更大规模的布局(拉网收割)、规划、拓展, 明确天花板、上下限, 敢于付出和收获



| 目标                   | 标准                                       |
| ---------------------- | ------------------------------------------ |
| 交付时间               | 更短                                       |
| 质量要求               | 更高                                       |
| 参与人员数             | 更少                                       |
| 同等时间内的需求变更数 | 更多                                       |
| 系统危险漏洞           | 更少                                       |
| 用户使用               | 更稳定、更快响应、更加便捷贴合业务及个性化 |
