<!-- ---
hide:
  - navigation
  - toc
--- -->

# [SONY](https://www.sony-semicon.com/en/index.html)
### Overview
[AITRIOS](https://www.aitrios.sony-semicon.com/) is an innovative solution from [Sony Semiconductor](https://www.sony-semicon.com/index.html) that leverages Edge Vision AI, IoT, and Cloud technologies to build a revolutionary ecosystem centered around Sony cameras.

### Responsibilities
As the sole Staff Cloud Engineer for Sony Semiconductor in China, my primary responsibilities included:
#### 1. System Integration
- Introduced [AITRIOS](https://www.aitrios.sony-semicon.com/) solution from Japan to China:
  - Migrated the solution from Azure Global to Azure China (operated by 21Vianet), addressing technical, compliance, security, and service availability challenges.
  - Collaborated with hardware and embedded teams to integrate cameras, motherboards (Raspberry Pi, custom versions), ESP32, and embedded software (FreeRTOS, Nuttx) into Azure China.

#### 2. Global Development
- **Frontend**: Led the Chinese team in refactoring the legacy Pro UI with Angular 16 and upgraded it to Angular 18.
- **Testing**: Established a frontend testing framework using Playwright.
- **Backend**: Redesigned the backend architecture with an abstraction layer to support multi-cloud compatibility (Alibaba Cloud, private cloud) alongside Azure services (Azure Functions, IoT Hub, CosmosDB, etc.).
- **Infrastructure as Code (IaC)**: Transitioned from ARM templates to Python, Ansible, and Terraform for multi-cloud deployment automation.
- Replaced Azure IoT Hub with ThingsBoard and performed customizations.

#### 3. Localization
- Gathered requirements from Chinese clients and translated them into technical specifications for global teams.
- Developed PoC systems tailored to local needs.
- Built a cloud resource management system using Django + Celery + Vue and IaC tools to reduce cloud costs by 40% in Azure China.

#### 4. Project Management
- Aligned milestones with global teams and ensured on-time delivery in China.
- Managed outsourcing teams, defined KPIs, and oversaw technical direction.

### Achievements
- Successfully localized the [AITRIOS](https://www.aitrios.sony-semicon.com/) project in China.
- Transformed the China team from an operations-focused group into a core development team.
- Received annual commendations from global leadership.

### Tech Stack
  - Cloud: Azure, Alibaba Cloud, Docker, K8S ...
  - Development: Python, FastAPI, Django, TypeScript, HTML3, CSS3, Angular, Vue, Java
  - IaC: ARM, Ansible, Terraform
  - IoT: Azure IoT Hub, ThingsBoard
  - Data: SQL Server, MySQL, PostgreSQL, CosmosDB, MongoDB, Kafka, Cassandra, InfluxDB

---

# [CreditEase](https://www.creditease.com/)
When I joined Creditease in 2016, my target is to develop a financial cloud platform based on OpenStack. 
After organizational changes in 2017, shifted focus to traditional IT operations, leading infrastructure integration and tool development to stabilize systems.

## CMDB System (Elephant)
### Overview
Around 2017, Creditease relied on manual processes and Excel spreadsheets for infrastructure management, resulting in severe information silos and inefficiencies. There was an urgent need for a CMDB system to centralize IT infrastructure management, improve operational efficiency, reduce risks, and support enterprise IT operations.    
### Features
- IDC Resource Lifecycle Management: Servers, virtual machines, storage devices, security appliances, spare parts, network segments, network circuits, domain names, DNS, etc.
- Software Lifecycle Management: Tracking and governance for software assets.
- Workplace Information Management: Centralized management of office locations and resources..
- Contract Management: Vendor contracts, SLAs, and compliance tracking.
- Cost Management: Cost allocation, settlement, and financial optimization.
- Duty Scheduling System: Automated shift planning and incident escalation.
- ...
### Responsibilities
Collaborated with cross-functional teams (IDC operations, networking, procurement, finance) to design and develop a CMDB system from scratch. Leveraged ITSM/ITIL best practices and industry references to:   

- Define unified data models and workflows for infrastructure assets.
- Automate resource discovery, inventory tracking, and lifecycle operations.
- Integrate with existing tools to break down information silos.
- Enable cost transparency and compliance across departments.
### Tech Stack
Python, Django, Celery, JQuery, Vue2, ECharts, Ansible ...

## Network-wide Monitoring System (Eagle)
### Overview
A comprehensive monitoring system was required to ensure service stability and operational reliability across all infrastructure resources.   
### Features
- Data Collection & Storage: Collected server, VM, and network device metrics, stored in ElasticSearch. 
- Visualization: Real-time dashboards built with Grafana and ECharts for system-wide visibility.  
- Alerting Engine: Custom rules for proactive incident detection and escalation.  
- **Workplace Monitoring**:  Deployed Raspberry Pi terminals across 1,000+ nationwide offices to monitor network health, enabling rapid fault localization and troubleshooting.
- **Network Check**
  - Extended workplace monitoring by deploying nodes across major cloud providers, achieving APM (Application Performance Monitoring) capabilities comparable to [TingYun](https://www.tingyun.com/).
  - Conducted exploratory commercialization efforts for the solution. 
### Responsibilities
Designed and developed the entire monitoring system from scratch, including:
- Architecture design for scalable data ingestion and storage.
- Integration of open-source tools (ElasticSearch, Grafana) with custom modules.
- Deployment automation for Raspberry Pi-based monitoring terminals.
- Cross-cloud node orchestration to enable unified performance insights.
### Tech Stack
Python, Django, Scrapy, Vue, Selenium, Prometheus, ElasticSearch, Grafana, Echarts, IPMI ...

## Database Operations Tool (DBAnt)
### Overview
DBAnt is a unified database operations tool designed for DBAs and data users to streamline database management and security.
### Features
- Unified Lifecycle Management: Managed 2,000+ production databases (Oracle/MySQL/Redis) across their lifecycle.
- Automated Workflows: Controlled all data queries, deployments, and exports through standardized processes. 
- Security Framework:
  - Built a pluggable encryption/decryption system to secure sensitive data.
  - Provided APIs and clients for secure data access across the organization.
- Infrastructure Automation:
  - Visual interface for database installation, deployment, backups, and recovery using Ansible.
  - Slow query log collection to Elasticsearch and analysis them to optimize performance.
- Monitoring & Compliance:
  - Dashboard visualization with ECharts and Grafana for real-time insights.
  - Met Deloitte internal audit requirements for data governance.
### Responsibilities
Independently designed, architected, and developed the entire system from scratch.
### Tech Stack
Django, Celery, Vue, Ansible, Prometheus, Elasticsearch, Grafana, ECharts, etc.

## Kubernetes-based PaaS Platform (Spider)
### Overview
In 2018, Creditease initiated the development of an internal Kubernetes-based private cloud. Initially managed by another team, the project was later merged into the Infrastructure Department. Following organizational adjustments, I took over part of its development and operations.
### Responsibilities
- Stability & Maintenance: Debugged critical issues and ensured cluster stability.
- Data Integration: Connected the PaaS platform with CMDB (Spider) and monitoring system (Eagle) for unified data visibility.
- Cloud Migration Strategy:
  - Cloud Adoption: Modernized legacy systems via Kubernetes migration and microservices transformation.
  - Cloud Repatriation: Migrated select applications from public cloud to private cloud to reduce costs.
- ...
### Tech Stack
Go, Gin, Java, Spring, Spring Cloud ...

## Traditional Middleware Operations
### Overview
Following workforce reductions and the centralization of infrastructure management at Creditease, operational responsibility for critical middleware components was transferred to the infrastructure team.
### Responsibilities
- Core Operations: Performed foundational tasks such as cluster provisioning, stability assurance, and scaling (up/down).
- System Prototyping: Designed a lightweight prototype for unified middleware management, but the system was not finalized or deployed due to organizational changes prior to my departure.
Middleware Scope:
- Message Queues & Streaming: ZooKeeper, Kafka, RocketMQ, RabbitMQ and etc.
- Elasticsearch.
- Microservices Components: Service discovery, API gateways, etc.  
### Tech Stack   
Ansible, Python, Shell

---



# [360](https://www.qianxin.com/)
## [Next Generation Security Operation Center(NGSOC)](https://www.qianxin.com/product/detail/pid/358)
### Overview
NGSOC Collected diverse security data and using various analytical methods to enable continuous cybersecurity posture monitoring.
### Responsibilities
- **Developer**: Develop security data integration tool, performing data cleansing and normalization to enable centralized information processing..
- **Project Manager**: Demonstrated exceptional technical expertise and leadership competencies, earning rapid promotion to Project Manager at Qingdao Customs. Ultimately resigned due to family care priorities after unsuccessful accommodation attempts regarding extended on-site assignments conflicting with childcare responsibilities.
### Tech Stack
Pyhton, SQL, Bash ...

---



# [IBM](https://www.ibm.com/us-en)
## Smart Cloud Orchestrator (SCO)
### Overview
SCO is an IBM-developed hybrid cloud solution built on OpenStack.
### Responsibilities
- **Installation**:  Packaged SCO modules into deployable product bundles using Ansible, Chef, and Bash, followed by rigorous validation.
- **Integration**: 
  - Merged OpenStack source code with custom-developed extensions.
  - Integrated IBM internal tools (ZVM, DB2, WebSphere) and third-party platforms (VMware).
- **Development**: Develop Dashboard and Nova components.
### Tech Stack
Python, Django, Ansible, Chef, Shell ...

## LinuxONE
### Overview
After the dissolution of the SCO China team, I joined the [LinuxONE](https://www.ibm.com/cn-zh/linuxone) team at IBM. LinuxONE aimed to build a cloud ecosystem combining standard Linux and OpenStack on IBM System z mainframes.
### Responsibilities
- OpenStack Migration: Ported OpenStack to IBM System z, enabling mainframes to leverage Linux and OpenStack ecosystems.
- Software Modernization: Collaborated with cross-functional teams to migrate IBM software (e.g., SPSS, DB2) to the LinuxONE platform.
- Ecosystem Visibility: Developed a web portal to showcase LinuxONE’s capabilities and integrations.
### Tech Stack
OpenStack, Django, Ansible, Chef, Java, SSH Stack (Struts, Spring, Hibernate) ... 

---

# [ATOS](https://atos.net/en/)
## Smart Grid System
### Overview
The ATOS Smart Grid Suite (ASGS) aimed to build a resilient, flexible, self-healing, and scalable next-generation smart grid system for ERDF(Electricité Réseau Distribution France) Linky project. As Europe’s largest smart grid initiative, the system supported 35 million smart meters and 700,000 data concentrators. Based on SOA principles and a classic JavaEE architecture, it provided a core Service Bus for external systems.
### Responsibilities
- Core Module Development: Stationed in Grenoble, France, collaborated with local teams to design and implement critical system components.
- System Integration: Validated end-to-end integration across smart meters, backend systems, and servers.
- Localization for China: Partnered with ZTE to establish a joint venture, delivering 3-phase POC projects for Southern Power Grid (Shenzhen), including localized adaptations and integrations.
### Tech Stack
Java, JavaEE, OSGi, Weblogic Service Bus ...

---

# [CIeNET](https://www.cienet.com/)
## Product Catalog
### Overview
Comverse (now part of [Amdocs](https://www.amdocs.com/)), a globally telecommunications support software provider, maintained numerous telecom BSS/OSS systems worldwide. These systems required nearly identical metadata for seamless interoperability. The Product Catalog served as a centralized tool for unified metadata maintenance, management, and distribution across all platforms.
### Responsibilities
Java Developer
### Tech Stack
Java Swing ...

---

# [Datang](https://www.datang.com/)
## Next Generation Billing System
### Overview
The next-generation provincial billing system for Datang Software, transitioning from a C/S (Client-Server) to B/S (Browser-Server) architecture.
### Responsibilities
Java Development
### Tech Stack
Java, Struts, J2EE, WebLogic ...

## Business Intelligence Systems
### Overview
A [Hyperion](https://www.oracle.com/cn/performance-management/hyperion-financial-management/) based business intelligence solution was deployed for China Unicom (formerly Netcom) in Chifeng and Baotou, Inner Mongolia. This operational analytics system integrated diverse data sources through ETL scripting, generated business intelligence reports, and provided critical insights for enterprise decision-making.
### Responsibilities
- Served as core developer during the Chifeng phase.
- Promoted to project lead for the Baotou implementation.
### Tech Stack
Hyperion, JavaScript, Oracle, Shell ...

## Liaoning Tietong BOSS System
### Overview
The Liaoning Tietong BOSS System was Datang Software’s first provincial-level project for Tietong (now part of China Mobile), providing critical support for Liaoning Tietong’s Business and Operations Support Systems (BOSS).
### Responsibilities
As Project Manager:
- Team Building: Assembled a core team at the Beijing headquarters and recruited local staff in Liaoning.
- Custom Development: Led on-site customized development using the company’s existing software stack.
- Execution: Oversaw data migration, system integration, and final delivery at the client’s location.
### Tech Stack
Java, J2EE, Struts, Tomcat, Weblogic, Informix, Hyperion, JavaScript ...