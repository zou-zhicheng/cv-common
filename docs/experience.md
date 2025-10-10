<!-- ---
hide:
  - navigation
  - toc
--- -->

<!-- https://codecv.top/ -->

# [索尼半导体](https://www.sony-semicon.com/cn/index.html)

### 公司与项目介绍

[索尼半导体](https://www.sony-semicon.com/cn/index.html) 是以 成像&感知技术为核心的半导体公司, [AITRIOS](https://www.aitrios.sony-semicon.com/)项目是以硬件为核心, 融合 Edge AI, Edge Computing, IoT, Cloud等技术的一整套端对端创新型解决方案.

### 工作内容

- **云迁移与运维**: 
  - 将 [AITRIOS](https://www.aitrios.sony-semicon.com/) 解决方案从日本引入到中国, 从 Azure全球 迁移 Azure中国(世纪互联), 解决其中的技术, 备案, 合规, 安全, 备份，日志，监控, 开发流程, 服务缺失等各项问题.    
- **全球开发**
  - 后端最初限定于Azure Cloud解决方案(Azure Function(Python), IoT Hub, Event Hub, CosmosDB, Key Vault...). 与全球团队合作, 将后端整体重构, 引入开源解决方案(Kubernetes(AKS), FastAPI, PostgreSQL, MongoDB, Thingsboard, ...), 进行多云适配(Azure/AWS/阿里云/私有云). 
  - 前端最早基于Pro UI构造, 性能和先进性上已远远不能满足需求, 率领中国团队以Angular 16进行重构, 并持续升级到Angular 18. 并使用 Playwright, NodeJS 建立了一套前端页面测试系统.
  - 初期系统部署采用 ARM(Azure Resource Manager) 进行自动化部署, 引入多云战略后, 采用 Terraform, Ansible, Python实现IaC. 
- **本地研发**
  - 搜集中国客户需求, 转发总部. 并开发PoC系统. 
- **项目管理**
  - 制定和监督项目进度, 管理外包团队, 制定考核标准, 监督交付效果, 引领技术方向.  

### 工作成就

- 将 [AITRIOS](https://www.aitrios.sony-semicon.com/) 项目成功在中国落地.  
- 将中国团队从运维团队转变成全球开发团队, 承担主力模块的开发. 
- 每年都获得总部的口头和书面嘉奖.  

### 技术栈

- 云: Azure, 阿里云, Docker, Kubernetes, Helm, Operator, nginx-ingress, Istio ...
- 开发: Python, FastAPI, Django, TypeScript, HTML3, CSS3, Angular, Playwright, Java ...
- IaC: ARM, Ansible, Terraform ...
- IoT: Azure IoT Hub, ThingsBoard, NodeRed ...
- 数据库: SQL Server, MySQL, PostgreSQL, CosmosDB, MongoDB, Kafka, Cassandra...

---

# [宜信](https://www.creditease.com/)
### 公司与项目介绍

[宜信](https://www.creditease.com/) 是金融科技的先行者, 作为基础架构部资深员工, 历经基础架构部从0到1的系统演进, 保障业务的稳定运行.

### 工作内容

- **私有云平台研发与运维**: 
  - 2017年宜信开始基于OpenStack构建金融云, 并根据企业情况不断进行演进, 历经Docker, Mesos,  最终构建起以 Kubernetes 为基础的企业云平台. 
  - 配合业务系统将相关业务微服务化, 使其能够在 K8S 上运行.
  - 配合业务系统将业务从公有云迁移到私有K8S平台.
- **可观测性体系**
  - 统一日志系统
  - 全网监控系统, 初期以Zabbix, 后期以Prometheus/ElasticSearch/Grafana为核心, 
  - 职场监控与**宜信测**: 高峰时宜信在全国拥有1000+的职场, 职场网络稳定稳定和排错需要大量人力, 我们通过创新型的在职场部署树莓派终端, 对职场网络进行快速进行定位与排查, 有效的监督职场网络, 保障服务的运行. 并在此基础上, 结合在主要云服务提供商部署节点, 实现类似 [听云](https://www.tingyun.com/) 效果的 **宜信测** 功能.  并进行了一些商业化的开拓. 
  - 链路追踪: 使用SkyWalking, OpenTelemetry等工具对链路追踪技术进行了小范围的尝试.
- **CMDB系统**: 从0设计, 研发CMDB, 实现了对基础设施生命周期的有效管理.
- **数据库运维系统(DBAnt)**: 基于金融数据的保密性特性, 从0设计开发了这套系统, 主要针对数据增删改查的行为, 设计加密解密系统, 增加权限和审批流程; 管理数据库生命周期; 图形化和自动化数据备份恢复操作; 自动收集分析慢日志数据, 为数据库优化提供支撑......
- **基础运维**: 例行性基础运维, 例如半自动化的提供一些基础中间件, 构建应用系统环境......

### 工作成就

- 通过自研与引入成熟工具, 初步建立了基础架构部的运维体系

### 技术栈

- Python, Django, Ansible, Celery, Vue, Echarts, Prometheus, Grafana, ElasticSearch, Java, Spring, Spring Cloud ...

---



# [奇安信](https://www.qianxin.com/)
### 工作内容与成就

- **[态势感知与安全运营平台(NGSOC)](https://www.qianxin.com/product/detail/pid/358)** 研发
- 青岛海关**态势感知与安全运营平台**项目经理, 负责定制化开发和实施。

### 技术栈

- Python, Django ...

---



# [IBM](https://www.ibm.com/cn-zh)
### 工作内容与成就

- SCO(Smart Cloud Orchestration)是IBM全球团队研发的基于OpenStack的混合云, 主要负责:   
  - Installation, 使用Ansible, Chef, Bash等工具将SCO中的各个模块整合成产品包, 并进行相关的验证.   
  - Integration, 集成OpenStack源代码, 二次开发代码, IBM内部的软件如ZVM, DB2, WebSphere等, 外部软件如Vmware.   
  - OpenStack Dashboard 等模块的二次开发.
- [LinuxONE](https://www.ibm.com/cn-zh/linuxone) - 带领团队在大型机SystemZ上构建基于Linux和OpenStack的软件生态平台.

### 技术栈

- Python, Django, Ansible, SaltStack, Java, Spring ......

---

# [源讯](https://atos.net/en/)
### 工作内容与成就

- 常驻法国Grenoble, 与法国工程师一道, 从事法国电网(ERDF)智能电网项目 [Linky](https://particulier.edf.fr/en/home/contract-and-consumption/meter/linky-meter.html) 的研发工作.
- 回国后, 与中兴成立合资公司, 进行本地化开发与部署, 推动智能电网项目在南方电网(深圳)的落地.

### 技术栈

- Java, Spring, WebLogic, Oracle ... 

---

# [瞬联](https://www.cienet.com/zh-hans)
### 工作内容与成就

- 参与 Comverse(现[Amdocs]( https://www.amdocs.com/)) 的离岸外包项目Product Catalog的研发工作, 该项目是一款基于Java Swing编写的对电信BOSS项目基础元数据进行管理的工具.

### 技术栈

- Java, Swing, Oracle ...

---

# [大唐电信](https://www.datang.com/)
### 工作内容与成就

- 基于J2EE开发的计费系统和经营分析系统的研发.
- 作为项目经理, 负责辽宁铁通大BOSS系统的本地化实施.

### 技术栈

- Java, JavaEE, Hibernetes, Struts, Oracle ...