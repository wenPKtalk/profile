# 文鹏坤

> 电话：`13571946597`       邮箱：`wensir_top@163.com`

<img src="https://cdn.jsdelivr.net/gh/wenPKtalk/pictures@master/blog/20250102/23_21/2851735830140_.pic.jpg" alt="avatar">

## 基本信息

### 西安工程大学 - 本科 - 电子信息与科学技术   (2012.09 - 2016.06)
**Github：** [github.com/wenPKtalk](https://github.com/wenPKtalk)   |  **个人博客：** [wenpktalk.github.io](https://wenpktalk.github.io/)
**英语:** 四级                                                  |  **工作年限：** 8年





- **曾获奖项：** 优秀毕业生

- **校园经历：** 连续三年成绩在本专业前十，在校完成课程要求外还能主动编码实践，并且在校外软件公司实习。



## 专业技能


- 擅长Java开发，**FullStack Develop，也有5年时间的前端开发经验，掌握React，Mobx,  Redux, nodejs等前端技术栈。**

- **有丰富的架构设计经验，熟练运用DDD，Clean Architecture，CQRS等架构风格，有微服务设计经验，掌握Spring Cloud 微服务全家桶。**
- **有长时间的TDD开发工作经验，对Unit Test 和Integration Test有深度的实践。**
- **熟练使用容器化技术原理Docker，k8s。有CI/CD devOps搭建经验对 gitlab-runner, github Action，Linux等基础设施有一定的了解和实践经历。**


- 熟练掌握stream, lambda ,函数式编程等java8新特性。熟练掌握java基础核心类库。熟练使用反射，**动态代理**，**nio**，**多线程**等相关知识。熟练掌握spring，springMVC，springBoot，mybatis，springDataJPA，mybatis等javaEE框架。

- **有丰富的敏捷开发流程经验**，熟练掌握版本控制Git工具。
- **熟练掌握java多线程，各种Lock，并发工具包，GC**。熟练使用常用的Guava，Apache Commons等类库。
- **线上服务性能诊断经验充分，经常负责服务性能优化，业务代码优化，有jvm调优实践，SQL调优实践，OOM 分析，大事务优化等丰富的工作实践。**
- 有丰富的后端大数据技术栈中的中间件：Kafka, Redis, Hbase使用经历，和有深度的技术了解。并在实际开发中有正确的选型和出现问题的调研与解决方案。



## 工作经验 （由近到远）

<div style="display: flex; justify-content: space-between;">
    <h3>全栈开发工程师- Essex Lake Group</h3> <p style="text-align: right">2021.03 - 至今</p>
</div>

- 负责ETL，Scheduler，Data Export 等模块技术调研与选型。**为项目需求、架构设计和编码标准的文档撰写做出贡献，促进团队成员间的知识共享和新成员的快速适应**。
- **On Call 和国际其他团队成员用英语沟通线上问题。**
- **负责模块任务拆分，MVP阶段划分，原子任务时间评估等前期准备工作。**
- **协助解决技术问题，展现解决问题的技巧和在快节奏环境下积极主动解决挑战的态度。** 
- 搭建本地开发环境，负责基础架构工作。
  












<div style="display: flex; justify-content: space-between;">
    <h3>后端开发工程师- 信大捷安西安研究院</h3> <p style="text-align: right">2019.03 - 2021.03</p>
</div>

- 负责“**安全会议**”，“**政务MDM**”等后端技术选型，代码规范等软件开发。
- **负责后端代码规范，指定代码提交CR, MR等规范，以及CI/CD流程搭建**。
- **协助解决技术问题，展现解决问题的技巧和在快节奏环境下积极主动解决挑战的态度。** 为项目需求、架构设计和编码标准的文档撰写做出贡献，促进团队成员间的知识共享和新成员的快速适应。
  
<div style="display: flex; justify-content: space-between;">
    <h3>全栈开发工程师- 上海京颐科技股份</h3> <p style="text-align: right">2016.07 - 2019.03</p>
</div>

- 负责**定制HIS系统开发，医保项目对接**等工作，多次出差到客户现场了解需求，调研现有设施。
- 和其他软件工程师一起拆解需求，指定交付计划。
- 到医院现场部署上线项目，确保项目稳定运行。


## 项目经历 （由近到远）

### Eye-Report

- 数据分析可视化项目生成快照截图，最后生成PDF并分发给客户。前端采用DOM快照，前端快照数据上传到后端后，后端采用HeadLess Browser对某一时刻数据可视化图表进行复原再截图，生成PDF。
- 前端采用了dom-to-image，对dom进行快照后，利用canvas复原生成图片，后端则采用了Playwright拉起一个无头浏览器进行截图。
- 后端使用了Spring-Retry 来避免文件上传的短暂文件服务不可用的重试。
- 后端使用Asynchronous, ThreadPoolService来保证服务并发度，使用Factory设计模式保证代码的整洁度。

### ETL

- **后端利用Antlr4解析器解析自定义表达式， ETL根据flow node生成对应的DSL 执行过程中通过DSL To Sql 进行持久化操作，通过引入高级语法DSL屏蔽数据库差异，抽象了ETL设计，做到了生成与底层存储的隔离**，
- 前端采用React + TypeScript 实现可拖动数据可视化操作。
- ETL引入了Jupiter Notebook 利用python代码操作。







### SaaS 安全应用

- 政务MDM应用，负责后端架构设计。
- **利用Java + Kafka MQ 进行指令下发，进行终端管控**。
- **设计 Kafka 使用过程中的消息幂等性，确保消息被消费等场景。**
- 负责线上问题support，其中定位Kafka使用过程中的一些棘手问题比如：Rebalance 造成的消费速度下降。
- 引入了ELK日志系统，可视化项目运行日志。


### SaaS 医疗系统

- HIS系统模块：挂号，收费，医保对接等模块开发。
- 针对各个省市区域的医保对接进行了设计总结，开发出第三方差异屏蔽系统 利用Spring boot + MySql等技术实现了医保对接接口的标准化。
### Other

- 主要技术都集中在Spring全家桶。
- 微服务有Spring Cloud
- 项目服务通信RPC框架有用过Thrift。