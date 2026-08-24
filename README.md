# 作品集
这里集中展示我围绕本地优先、可解释流程和真实业务场景完成的产品原型、交付实验与工具。

## 产品与业务原型
| 项目 | 简介 | 技术与特点 |
|---|---|---|
| [Smart‑Enterprise‑ERP管理系统](https://github.com/suhuideyu/Smart-Enterprise-ERP-Management-Platform) | 面向中小企业的企业资源管理业务原型，围绕基础业务流程、权限管控、业务单据流转完成需求梳理、原型实现与方案验证，模拟售前阶段业务调研与方案交付过程。 | Java、Spring Boot、Vue3、MySQL；业务流程建模、角色权限体系，保留业务原型说明与来源注释。 |
| [智询工坊-设备商品 RAG 问答系统](https://github.com/suhuideyu/device‑rag‑qa‑agent) | 面向设备商品知识库的RAG智能问答Agent原型，完成PDF文档解析处理、向量库入库、意图识别、多路检索、多轮问答链路；实现知识库导入与智能问答两大业务流程验证。 | Python、LangChain、LangGraph、Milvus、MongoDB；Prompt工程、多路检索融合、状态化Agent编排，保留流程原型与测试说明。 |
| [MockMaster‑AI面试平台](https://github.com/suhuideyu/MockMaster‑AI‑Interview‑Platform) | 面向求职场景的AI模拟面试业务原型，完成业务需求拆解、交互流程设计与系统落地；模拟解决方案场景下面向终端用户的产品方案设计与功能交付。 | Spring Boot、Vue、大模型集成；接口联调、评测业务逻辑，完整保留原型文档与方案说明。 |
| [taobao‑beauty‑double11](https://github.com/suhuideyu/taobao‑beauty‑double11‑course‑completion) | 美妆电商大促业务原型，覆盖电商后台业务管理、前端业务门户，配套Spark‑ETL数据处理链路；模拟大促场景下业务系统与数据链路联合交付验证。 | SpringBoot、Vue、MySQL、Spark‑Scala；业务应用与批处理ETL联合，标注业务场景边界与测试说明。 |


## 本地优先工具
| 项目 | 简介 | 技术与特点 |
|---|---|---|
| [个人求职作品集](https://github.com/suhuideyu/junruguo-portfolio) | 面向售前与解决方案工程师岗位的中文个人网站源码。 | React、TypeScript、GSAP；响应式排版、低动态模式，静态部署。 |
| [ppt生成器Skill](https://github.com/suhuideyu/skills/tree/main/ppt-generator) | PPT批量生成工具，基于本地模板完成演示文稿输出，全部文件本地处理。 | Python脚本、PPT模板引擎；本地优先，不向外提交用户文档数据。 |
| [JobArchive-网申助手](https://github.com/suhuideyu/JobArchiveTool) | 浏览器扩展：预览、脱敏并辅助填写网申表单，不自动提交。 | Chrome/Edge Extension；不自动提交、不上传隐私资料。 |
| [douyin_opinion_analysis](https://github.com/suhuideyu/douyin_opinion_analysis) | 公开网络评论采集、数据预处理、可视化及文本智能分析工具。 | Python、网络爬虫、NLP文本分析、数据可视化；遵循本地优先设计，原始采集数据不在本地文件系统持久留存，业务有效数据持久存放于数据库。 |

## 学习与其他实践
| 项目 | 简介 | 技术与特点 |
|---|---|---|
| [校园二手集市](https://github.com/suhuideyu/campus_bazaar-Course-Design-Project) | 校园二手集市课程设计项目，实现二手物品交易基础业务闭环。 | Spring Boot、Vue3、MySQL；前后端分离，课程实践原型。 |
| [learn-to-Multi-Agent_SyetemDesign](https://github.com/suhuideyu/learn-to-Multi-Agent_SyetemDesign) | 多智能体系统学习实验，探索多Agent任务拆解与协同执行流程。 | Python、大模型调用；多角色任务调度实验。 |
| [card-demo](https://github.com/suhuideyu/card-demo) | 前端组件布局练习Demo，用于页面交互与样式学习。 | HTML、CSS；前端基础练习。 |
| [ant-online-training-materials](https://github.com/suhuideyu/ant-online-training-materials) | 线上技术实训资料集合，存放随堂练习、实验案例与学习记录。 | Java、Python；课程学习沉淀。 |

## 设计原则
- **本地优先**：个人资料、文档素材与离线包默认不上传。
- **真实边界**：对外部数据、系统估算与本地兜底明确标注。
- **人工确认**：涉及提交、修改、删除和敏感填写时保留用户最终决定权。
