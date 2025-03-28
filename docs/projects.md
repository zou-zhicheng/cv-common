<!-- ---
hide:
  - navigation
  - toc
--- -->

# 索尼
### 项目简介
[AITRIOS](https://www.aitrios.sony-semicon.com/) 是 [索尼半导体](https://www.sony-semicon.com/index.html) 构建的新一代革命性产品, 利用 Edge Vision AI, IoT, Cloud 等技术在构建一套革命性的生态系统.

### 主要工作
作为索尼半导体在中国唯一的Cloud Engineer Staff, 主要从事了如下工作.
#### 系统集成
将 [AITRIOS](https://www.aitrios.sony-semicon.com/) 解决方案从日本引入到中国, 包括 
- 将服务器端解决方案从 Azure全球 迁移 Azure中国(世纪互联), 解决其中的技术, 备案, 合规, 安全, 服务缺失等各项问题.
- 与硬件团队合作, 将摄像头, 主板(树莓派, 定制版), ESP32, 嵌入式软件(FreeRTOS, Nuttx)等集成在一起, 逐步调试, 接入到 Azure中国(世纪互联).

#### 全球开发
- 前端最早基于Pro UI构造, 性能和先进性上已远远不能满足需求, 率领中国团队以Angular 16进行重构, 并持续升级到Angular 18.
- 使用 Playwright 建立了一套前端页面测试系统.
- 后端最初限定于Azure Cloud解决方案(Azure Function, IoT Hub, Event Hub, CosmosDB, Key Vault...), 与全球团队合作, 将后端整体重构, 引入抽象层, 进行多云适配(阿里云, 私有云).   
- 初期系统部署采用 ARM(Azure Resource Manager) 进行自动化部署, 引入多云战略后, 采用 Python, Ansible, Terraform实现IaC.   
- 将Azure IoT Hub替换为ThingsBoard, 并对ThingsBoard做一些二次开发工作.

#### 本地需求
- 搜集中国客户需求, 并将需求转换成需求文档和开发文档提交给总部.   
- 根据中国客户开发一些简单的PoC系统.   
- 在Azure中国缺乏Automation组件的情况下, 根据FinOps的基本原则, 使用Django + Celery + Vue 的技术栈, 结合IaC工具, 对云资源进行管理和调度, 为公司节省了 40% 左右的云开销.   

#### 项目管理
- 与总部确立里程碑任务, 并在中国落实.   
- 管理外包团队, 制定考核标准, 监督交付效果, 引领技术方向.   

### 项目成就
- 将AITRIOS项目成功在中国落地.   
- 将中国团队从运维团队转变成全球开发团队, 承担主力模块的开发.   
- 每年都获得总部的口头和书面嘉奖.    

### 技术栈
- Azure Cloud, Azure Funtion, Azure IoT Hub, Azure Event Hub, Azure AKS, Key Vault ...
- Aliyun Cloud
- ARM / Ansible / Terraform
- FastAPI / Django
- Angular 16 / Angular 18 / Vue3 / Element UI / Playwright
- Java / ThingsBord
- SQL Server / MySQL / PostgreSQL / CosmosDB

---

# 宜信
2016年加入宜信之初, 主要任务是以OpenStack为基础, 与合作伙伴一起共建金融云平台.   
2017年公司组织结构调整, 放弃金融云平台, 转向传统运维. 帮助总公司对各子公司进行基础架构资源整合, 结合自己对于运维,ITSM,ITIL的理解, 挖掘公司痛点, 发挥开发特长, 架构, 开发和维护了一系列运维工具, 帮助公司快速的完成了基础架构的统一和稳定运行.   
## CMDB系统(Elephant)  
2017年左右的宜信是一家在基础架构管理上很原始的公司, 主要依赖人和Excel表格传递信息, 信息缺失, 信息离散, 信息不一致问题非常严重.   
与IDC基础运维人员合作, 结合自己对ITSM, ITIL的相关理解, 参考行业相关实现, 并与采购部门, 财务部门合作, 从0开发了一套CMDB系统。   
主要包含如下功能: 
- IDC拓扑。
- 服务器，虚拟机, 存储设备，安全设备，配件等的自动发现, 远程操作, 告警信息收集和生命周期管理。
- 网段，线路，域名, DNS管理。
- 职场信息管理。
- 合同管理，成本分摊管理。
- ...

## 全网监控系统(Eagle)    
在CMDB的基础上, 需要对各种资源进行监控.   
- 使用 PING, IPMI, Prometheus 收集服务区, 虚拟机, 网络设备等信息.   
- 在ElasticSearch中进行存储.
- 利用Grafana和Echarts进行大屏展示.  
- 开发告警引擎.   
- 针对高峰时2000+的职场, 通过在职场部署树莓派终端, 以及在主要云服务提供商部署节点,实现类似 [听云](https://www.tingyun.com/) 效果的宜信测功能. 有效的监督职场网络, 保障服务的运行. 并进行了一些商业化的开拓.   

## 
## 成就

## 技术栈
- Python / Django / Celery
- JQuery / Vue2 / ECharts
- Ansible
- Prometheus / ElasticSearch / Grafana
- 树莓派

---

# IBM

---

# 源讯

---

# 瞬联

---

# 大唐电信

---

???+ info "Developing a platform to automate work contracts for Optum Vendors and Clients"

    ### Project Summary

    Developing a platform to automate and ease out contract management for the external stakeholders in the company's initiative.

    ### Methodology

      - Worked on database and front-end development by using Angular, JavaScript and SQL Server technologies
      - Automated auto approval and data updating mechanism using Azure functions and .NET Core based webjobs
      - Created CI-CD pipelining using GitHub actions to automate deployment
      - Integrated SSO authentication into platform by using Ping federate and organization’s Azure AD

    ### Deliverables

      - Developed a process to automate data sanity by syncing with external data source with zero manual intervention
      - Devised a model of email-based approval process to perform verification, auditing and versioning of contracts
      - Optimized first load time by lazy loading heavy components and SSO to minimize time-to-interact on platform
      - Directly create incident with ServiceNow platform to simplify client request mngt. and query resolution

    ### Achievements
    - Recognized for the contributions in project with 6 internal Bravo awards

    ### Techstacks Used

     Angular 9, .NET Core, Kendo UI, SQL Server, Github Actions, Azure Web jobs

??? info "Automated NPS score decrement factors of Claims related calls using Angular, Python and BARD libraries"

    ### Project Summary

    Web application to simplify resource requirement planning for the various department in the company.

    ### Methodology

      - BARD libraries used to classify consumer calls responses into possible categories
      - Cloud storage to save monthly call information for handy access
      - Angular based platform for uploading excel related data and dashboard view

    ### Deliverables

    Complete automation of improving NPS score related insights for Claims team which otherwise required
    manual listening and then classifying the calls for possible improvements

    ### Techstacks Used

    Angular 9, ngPrime, .NET Core, SQL Server, Github Actions

??? info "Developing a documentation site for all the applications"

    ### Methodology

    - Created using low code technologies including MKDocs and Git
    - Automated editing and deployment using Git pull requests and Actions
    - Very fast loading time (<1 sec) and can be easily edited by non-coders as it uses markdown.

    ### Techstacks Used

    MkDocs, Azure Object Storage, Github Actions

---

<!-- [ Back to Home](./index.md){ .md-button } -->
