<!-- ---
hide:
  - navigation
  - toc
--- -->

# [索尼](https://www.sony-semicon.com/cn/index.html)
### 项目简介
[AITRIOS](https://www.aitrios.sony-semicon.com/) 是 [索尼半导体](https://www.sony-semicon.com/index.html) 创新解决方案, 利用 Edge Vision AI, IoT, Cloud 等技术在构建一套以索尼摄像头为核心的革命性的生态系统.

### 主要工作
作为索尼半导体在中国唯一的Staff Cloud Engineer, 主要从事了如下工作:
#### 1. 系统集成
将 [AITRIOS](https://www.aitrios.sony-semicon.com/) 解决方案从日本引入到中国, 包括 
- 将解决方案从 Azure全球 迁移 Azure中国(世纪互联), 解决其中的技术, 备案, 合规, 安全, 服务缺失等各项问题.
- 与硬件团队和嵌入式团队合作, 将摄像头, 主板(树莓派, 定制版), ESP32, 嵌入式软件(FreeRTOS, Nuttx)等集成在一起, 逐步调试, 接入到 Azure中国(世纪互联).

#### 2. 全球开发
- 前端最早基于Pro UI构造, 性能和先进性上已远远不能满足需求, 率领中国团队以Angular 16进行重构, 并持续升级到Angular 18.
- 使用 Playwright 建立了一套前端页面测试系统.
- 后端最初限定于Azure Cloud解决方案(Azure Function, IoT Hub, Event Hub, CosmosDB, Key Vault...), 与全球团队合作, 将后端整体重构, 引入抽象层, 进行多云适配(阿里云, 私有云).   
- 初期系统部署采用 ARM(Azure Resource Manager) 进行自动化部署, 引入多云战略后, 采用 Python, Ansible, Terraform实现IaC.   
- 将Azure IoT Hub替换为ThingsBoard, 并对ThingsBoard做一些二次开发工作.

#### 3. 本地需求
- 搜集中国客户需求, 并将需求转换成需求文档和开发文档提交给总部.   
- 根据中国客户开发一些简单的PoC系统.   
- 在Azure中国缺乏Automation组件的情况下, 根据FinOps的基本原则, 使用Django + Celery + Vue 的技术栈, 结合IaC工具, 对云资源进行管理和调度, 为公司节省了 40% 左右的云开销.   

#### 4. 项目管理
- 与总部确立里程碑任务, 并在中国落实.   
- 管理外包团队, 制定考核标准, 监督交付效果, 引领技术方向.   

### 项目成就
- 将 [AITRIOS](https://www.aitrios.sony-semicon.com/) 项目成功在中国落地.   
- 将中国团队从运维团队转变成全球开发团队, 承担主力模块的开发.   
- 每年都获得总部的口头和书面嘉奖.    

### 技术栈
  - 云: Azure, 阿里云, Docker, K8S ...
  - 开发: Python, FastAPI, Django, TypeScript, HTML3, CSS3, Angular, Vue, Java
  - IaC: ARM, Ansible, Terraform
  - IoT: Azure IoT Hub, ThingsBoard
  - 数据库: SQL Server, MySQL, PostgreSQL, CosmosDB, MongoDB, Kafka, Cassandra, InfluxDB

---

# [宜信](https://www.creditease.com/)
2016年加入宜信之初, 主要任务是以OpenStack为基础, 与合作伙伴一起共建金融云平台.   
2017年公司组织结构调整, 放弃金融云平台, 转向传统运维. 帮助总公司对各子公司进行基础架构资源整合, 结合自己对于运维,ITSM,ITIL的理解, 挖掘公司痛点, 发挥开发特长, 架构, 开发和维护了一系列运维工具. 帮助公司快速的完成了基础架构的融合和稳定运行.   

## CMDB系统(Elephant)  
### 项目简介
2017年左右的宜信是一家在基础架构管理上很原始的公司, 主要依赖人和Excel表格传递信息, 信息孤岛等问题非常严重.  急需一套CMDB系统管理和维护整个IT基础设施, 提高工作效率, 降低风险, 并为企业的IT运营和管理提供支持。    
### 系统功能
- IDC资源生命周期管理, 包含服务器, 虚拟机, 存储设备, 安全设备, 配件, 网段, 网络线路, 域名, DNS等.
- 软件生命周期管理。
- 职场信息管理.
- 合同管理.
- 成本管理, 合理进行成本分摊和结算.
- 值班系统.
- ...
### 主要工作
与IDC基础运维人员, 网络部门, 采购部门, 财务部门等合作, 结合自己对ITSM, ITIL的相关理解, 参考行业相关实现, 从0开始, 设计, 架构和开发了一套CMDB系统. 
### 技术栈
Python, Django, Celery, JQuery, Vue2, ECharts, Ansible ...

## 全网监控系统(Eagle)  
### 项目简介
需要对资源进行监控以保障服务的稳定运行.   
### 系统功能
- 采集服务器, 虚拟机, 网络设备等信息, 在ElasticSearch中进行存储. 
- 利用Grafana和Echarts进行大屏展示.  
- 告警引擎开发.  
- **职场监控**:  高峰时宜信在全国拥有1000+的职场, 职场网络稳定稳定和排错需要大量人力, 我们通过创新型的在职场部署树莓派终端, 对职场网络进行快速进行定位与排查, 有效的监督职场网络, 保障服务的运行.
- **宜信测**:  在职场监控树莓派的基础上, 结合在主要云服务提供商部署节点, 实现类似 [听云](https://www.tingyun.com/) 效果的 **宜信测** 功能.  并进行了一些商业化的开拓. 
### 主要工作
从0开始设计,架构和开发整套监控系统
### 技术栈
Python, Django, Scrapy, Vue, Selenium, Prometheus, ElasticSearch, Grafana, Echarts, IPMI ...


## 数据库运维系统(DBAnt)
### 项目简介
DBAnt是提供给DBA, 数据调用人员的统一的数据库运维工具.
### 系统功能
- 统一管理2000+生产数据库(Oracle/MySQL/Redis)的生命周期.
- 设计流程接管所有的数据查询, 发布与导出. 
- 设计可插拔加密解密系统保障数据库安全, 为公司所有的数据查询提供API, client等. 
- 可视化界面调用ansible进行数据库安装部署, 备份与恢复. 
- 使用ElasticSearch收集慢日志, 分析,为数据库优化提供建议. 
- Echarts, Grafana大屏展示. 
- 满足德勤内审需求. 
### 主要工作
从0开始, 独自完成所有的设计,架构和开发.
### 技术栈
Django, Celery, Vue, Ansible, Prometheus, ElasticSearch, Grafana, Echarts ...

## 基于K8S的PaaS平台(Spider)
### 项目简介
宜信在2018年开始在内部开发基于K8S的私有云, 最初由其他部门负责, 后期合并到基础架构部, 并且随着人员调整, 我接手其中一部分的开发与运维工作.
### 主要工作
- 修复Bug, 维护服务器集群稳定.
- 将CMDB(Spider)和监控系统(Eagle)中的数据与PaaS平台(Spider)打通.
- 配合与响应内部系统 **上云**(将原有系统K8S化, 微服务化) 和 **下云**(将一部分应用服务从公有云迁移到私有云以降低成本) 需求.
- ...
### 技术栈
GO, Gin, Java, Spring, Spring Cloud ...


## 中间件等传统运维
### 项目简介
宜信后期人员锐减以及总部统一了所有的基础架构, 需要对一系列的中间件运维起来.
### 主要工作
主要做一些基础运维, 例如创建集群, 负责稳定性, 扩缩容等。 本来准备构建一个系统去统一管理, 并做了一点简单原型, 但之后就离职了, 并未形成持续在用的稳定系统. 
相关的中间件主要包括:
- 消息队列和流： Kafka、 RocketMQ、RabbitMQ ...
- 分布式日志系统：Elasticsearch
- 微服务相关组件等  
### 技术栈   
Ansible, Python, Shell
---

# [IBM](https://www.ibm.com/cn-zh)
## Smart Cloud Orchestrator (SCO)
### 项目简介
SCO是IBM以OpenStack为基础, 整合IBM内部资源进行对计算, 存储, 网络等资源进行管理, 为企业构建易于使用, 安全, 可扩展的私有,公有和混合云.  
### 主要工作
- **Installation**: 使用Ansible, Chef, Bash等工具将SCO中的各个模块整合成产品包, 并进行相关的验证.
- **Integration**: 集成OpenStack源代码, 二次开发代码, IBM内部的软件如ZVM, DB2, WebSphere等, 外部软件如Vmware.
- **Development**: 基础组件如 Dashboard, Nova的边缘性开发工作.
### 技术栈
Pyhton, Django, Ansible, Chef, Shell ...

## [LinuxONE](https://www.ibm.com/cn-zh/linuxone)
### 项目简介
SCO中国团队解散之后, 加入 SystemZ LinuxONE 团队, [LinuxONE](https://www.ibm.com/cn-zh/linuxone) 尝试在IBM SystemZ 上构建普通Linux和OpenStack的云生态. 
### 主要工作
- 将 OpenStack 在 IBM SystemZ 大型系统上做迁移, 让System Z能够享受到 Linux 和 OpenStack 的生态系统.
- 配合其他部门做IBM的一些软件进行迁移, 例如 SPSS, DB2...
- 创建 Web Portal 展示 LinuxONE 生态.
### 技术栈
OpenStack, Django, Ansible, Chef, Java, SSH(Struts, Spring, Hibernetes) ... 

---

# [源讯](https://atos.net/en/)
## 智能电网系统
### 项目简介
ATOS Smart Grid Suit (ASGS)目标是为法国电力公司(ERDF) Linky项目建立一套坚强, 灵活, 自愈, 易扩展的新一代智能电网系统, 项目达到3500万台智能电表, 70万台集中器的规模, 为欧洲第一的智能电网系统. 系统基于SOA理念, 采用经典的JavaEE架构,  向外部系统提供核心的Service Bus.
### 主要工作
- 常驻法国Grenoble, 与法国同事一起, 研发核心模块.
- 系统集成, 负责从电表, 集中器, 系统, 服务器的集成和验证.
- 与中兴成立了合资公司, 合建南方电网(深圳)项目, 共3期POC, 负责一些本地化的开发和集成工作.
### 技术栈
Java, JavaEE, OSGi, Weblogic Service Bus ...

---

# [瞬联](https://www.cienet.com/zh-hans)
## Product Catalog
### 项目简介
Comverse(现[Amdocs](https://www.amdocs.com/))作为全球知名的电信支撑软件运营商, 在全球维护了众多的电信支撑系统, 而所有的这些系统都需要近乎相同的元数据, Product Catalog就是一款统一的维护, 管理, 分发的元数据管理软件.   
### 主要工作
Java开发
### 技术栈
Java Swing ...

---

# [大唐电信](https://www.datang.com/)
## 计费系统研发
### 项目简介
大唐软件下一代省级计费系统, 实现从 C/S 模式到 B/S 模式的转变.   
### 主要工作
Java开发
### 技术栈
Java, Struts, J2EE, Weblogic ...

## 经营分析系统
### 项目简介
基于 Hyperion 的商业智能解决方案, 在内蒙古赤峰和包头网通(现中国联通)承建了经营分析系统, 通过对各种源数据进行分析, 创建ETL脚本清理整合数据, 创建经营分析报表, 为企业经营决策提供支撑.
### 主要工作  
在赤峰项目的时候是开发核心主力, 包头项目的时候已升任项目负责人.
### 技术栈
Hyperion, JavaScript, Oracle, Shell ...

## 辽宁铁通BSS/OSS系统
### 项目简介
辽宁铁通BSS/OSS系统是大唐软件获得的第一个铁通省级项目, 为辽宁铁通的BOSS业务提供支撑.
### 主要工作
做为项目经理, 在北京总部组件团队, 同时在辽宁分支机构招聘人员, 利用公司现有软件, 在客户现场做定制化开发, 数据迁移, 交付与集成。  
### 技术栈
Java, J2EE, Struts, Tomcat, Weblogic, Informix, Hyperion, JavaScript ...