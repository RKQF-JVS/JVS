
### **项目介绍：**

- JVS是什么？

  JVS是企业级应用构建的基础脚手架，提供开箱即用的基础功能集成，其中集成了 账户管理、租户管理、用户权限体系、三方登录、环境配置、各种业务日志等功能，还提供了对接 低代码、数据中台的能力。

- JVS能解决什么？

  JVS能降低开发团队构建基础框架的难度，能为企业提供完整的一体化、私有部署的数字底座，并提供完整的企业数字化应用的完整的解决方案。基础框架提供100%的源码开源，提供商用级的可插拔应用模块和服务，支持原生应用的开发与低代码/无代码的轻应用的配置拓展。

- JVS和其他产品区别

  JVS不仅仅是一个框架，具备无限的可能性（可以对接低代码式的业务中台与数据中台）；JVS不仅仅是一堆代码，具备专业的支持团队（服务社群）；JVS不仅仅是基础技术，具备多种企业级场景的完备的解决方案与配套的定制开发服务。

- JVS整体产品体系

  JVS不仅仅是一个框架，是一个完整的企业数字化的解决方案，包括基础框架、业务能力、上层应用等。
![输入图片说明](img/jvs%E4%BA%A7%E5%93%81%E4%BD%93%E7%B3%BB.png)



### **项目构成**

- 框架前端地址：https://github.com/RKQF-JVS/jvs-ui
- 框架后端地址：https://github.com/RKQF-JVS/jvs


### **体验地址与账号说明**
![输入图片说明](img/image%E4%BD%93%E9%AA%8C.png)
账号说明：

- 普通用户端：体验者自有微信扫码登录
- 管理端(全网共享)：testadmin  123456
- 管理端+应用编辑：联系运营微信号 ruanjbz，开设独立环境与独立账号
- 管理端+平台配置+应用编辑：联系运营微信号 ruanjbz，获取私有化部署文档与安装包


地址说明：

- 管理平台（含管理平台、低代码）：https://frame.bctools.cn/
- 数据智仓（数据分析平台）：http://bi.bctools.cn/
- 企业文档：http://knowledge.bctools.cn/
- 企业计划（项目管理）：http://teamwork.bctools.cn/
- 企业邮筒（Web邮箱客户端）：http://mailbox.bctools.cn/
- 规则引擎：http://rules.bctools.cn/
- 逻辑引擎：http://logic.bctools.cn/
- 视频会议：http://meeting.bctools.cn/



### 部署文档

https://github.com/RKQF-JVS/jvs/blob/2.1.5/docker-compose/readme.md  

### 部署视频

https://www.bilibili.com/video/BV15e411u7wQ?share_source=copy_web&vd_source=84d509be6d513ddc55eb13d4bd45cf90  


**物理拓扑：
![输入图片说明](img/image11.png)


**技术栈说明：**

|                | **组件名称**                               | **组件作用**     | **开源协议** |      |
| -------------- | ------------------------------------------ | ---------------- | ------------ | ---- |
| 表现层（前端） | EsLint                                     | 前端代码质量检测 | MIT          |      |
| Vuex           | 前端框架                                   | MIT              |              |      |
| Element-ui     | 前端组件库                                 | MIT              |              |      |
| Crypto-Js      | 前端加密                                   | BSD              |              |      |
| axios          | 基于promise用于浏览器和node.js的http客户端 | MIT              |              |      |
| data-set       | 前端数据绑定                               | MIT              |              |      |
| vue-router     | 前端路由                                   | MIT              |              |      |
| v-charts       | 图形化组件渲染                             | MIT              |              |      |
| E-charts       | 图形化组件渲染                             | Apache 2.0       |              |      |
| WebPack        | 前端代码打包                               | MIT              |              |      |
| G2             | 图形化组件渲染                             | MIT              |              |      |
| G6             | 图形化组件渲染                             | MIT              |              |      |
|                |                                            |                  |              |      |

| **组件归属**           | **组件名称**   | **组件作用**      | **开源协议** |      |
| ---------------------- | -------------- | ----------------- | ------------ | ---- |
| 应用逻辑层（后端框架） | Lombok         | 代码精简          | MIT          |      |
| Mybatis plus           | 数据持久层     | Apache 2.0        |              |      |
| Hutool                 | 底层工具集     | 木兰宽松许可证 V2 |              |      |
| Swagger                | 在线接口文档   | Apache 2.0        |              |      |
| Groovy                 | 敏捷脚本语言   | Apache 2.0        |              |      |
| Spring boot            | 基础脚手架     | Apache 2.0        |              |      |
| spring cloud alibaba   | 微服务框架     | Apache 2.0        |              |      |
| Xxl-job                | 定时任务       | GNU 3.0           | 通过端口调用 |      |
| Nacos                  | 注册中心       | Apache 2.0        |              |      |
| Sentinel               | 接口限流       | Apache 2.0        |              |      |
| seata                  | 分布式事务处理 | Apache 2.0        |              |      |
| Skywalking             | 链路跟踪       | Apache 2.0        |              |      |
| Redisson               | 分布式锁       | Apache 2.0        |              |      |
| RabbitMq               | 消息队列       | MPL 1.1           |              |      |
| Kafka                  | 分布式消息队列 | Apache 2.0        |              |      |

| **组件归属** | **组件名称**            | **组件作用**                 | **开源协议** |      |
| ------------ | ----------------------- | ---------------------------- | ------------ | ---- |
| 数据存储层   | ElasticSearch           | 文件搜索引擎（日志、打文本） | Apache 2.0   |      |
| Mongo        | 分布式文件存储数据库    | Apache 2.0                   |              |      |
| Mysql        | 关系型数据库            | GPL                          | 通过端口调用 |      |
| MariaDB      | MYSQL集群               | GNU 2.0                      | 通过端口调用 |      |
| mycat        | 数据分库                |                              |              |      |
| Redis        | 高性能的key-value数据库 | BSD 3                        |              |      |

| **组件归属** | **组件名称** | **组件作用** | **开源协议** |      |
| ------------ | ------------ | ------------ | ------------ | ---- |
| 运维支持层   | Docker       | 容器         | Apache 2.0   |      |
|              |              |              |              |      |

## **系统部分截图：**
### 登陆页面
![输入图片说明](img/image%E7%99%BB%E9%99%86%E9%A1%B5%E9%9D%A2.png)

### 登陆首页
![输入图片说明](img/%E9%A6%96%E9%A1%B5%E7%95%8C%E9%9D%A2.png)

### 应用模板中心
支持一键安装应用
![输入图片说明](img/image%E6%A8%A1%E6%9D%BF%E4%B8%AD%E5%BF%83.png)
### 框架基础功能
![输入图片说明](img/image%E5%9F%BA%E7%A1%80%E5%8A%9F%E8%83%BD.png)

### 列表配置
![输入图片说明](img/image%E5%88%97%E8%A1%A8%E9%A1%B5%E9%85%8D%E7%BD%AE.png)
### 流程配置
![输入图片说明](img/image%E6%B5%81%E7%A8%8B%E9%85%8D%E7%BD%AE.png)
### 表单配置
![输入图片说明](img/image%E8%A1%A8%E5%8D%95%E9%85%8D%E7%BD%AE.png)

### 逻辑配置
![输入图片说明](img/%E9%80%BB%E8%BE%91%E5%BC%95%E6%93%8E%E9%85%8D%E7%BD%AE%E6%88%AA%E5%9B%BE.png)
### 数据加工引擎
![输入图片说明](img/image%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86.png)

### 图表配置
![输入图片说明](img/image%E5%9B%BE%E8%A1%A8.png)

### 使用与授权
在合规备案情况下，支持自用与商用，商用提供100%源代码。
### 版本说明：
使用用途|费用模式|使用条件|授权时间
-|-|-|-
个人学习|免费|免费备案|永久
商用、二次开发|收费、代码交付|技术服务合同+商用备案|永久

### 商用费用说明：
> 技术服务费，必选，具体费用请与商务沟通
> 定制开发费，可选，1500元/人天
> 部署费用，可选，500元/次
> 长期运维，可选，协商

备案说明：联系我们的商务人员，在线备案，备案内容：项目名称，使用模式（自用/商用），备案主体主体，备案联系人员，即可。
### 禁止行为（为了保障产品走得更远）：
* 在未获得我方认可分发代码的情况下，禁止以任何形式进行代码分发（包含但不限于代码拷贝、代码公开、代码开源、代码分享等行为）
* 禁止在未备案的情况下，私自使用（包含自用与商用）

## **技术交流与商务支持：**

![群二维码](https://github.com/RKQF-JVS/jvs/assets/94048608/25b3f799-8d9c-4eff-9987-daac561070b7)





如因人数限制无法加群时，可加运营同学拉入技术交流群

![输入图片说明](https://foruda.gitee.com/images/1693376631879434922/54ec140e_10006021.png "屏幕截图")
