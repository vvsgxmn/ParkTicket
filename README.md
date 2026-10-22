## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

# 基于SpringBoot+Vue的游乐场购票系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

本系统是一款面向大型主题乐园票务与游园服务的数字化平台，针对线下购票排队久、票种权益规则复杂、设施排队不透明、纸质门票易丢失且核验慢、园区经营缺少客流与票务洞察等问题，把游客选票实名预约、余额支付、电子凭证核销、设施排队与演艺时刻、公告攻略与评价，以及管理端园区档案、票务订单与 ECharts 经营驾驶舱整合到同一套前后端分离工程中。

系统采用 SpringBoot + Vue 架构，区分普通游客与乐园管理员：游客端完成浏览选票、实名下单、余额支付、核销码出示与设施/演艺查询；管理端维护分区设施、票种库存、订单退款、入园核销与经营 KPI。购票从待付款→待核销→核销完成可追溯，未支付可取消、已支付可按规则退款，适合毕设、课设与乐园票务学习参考。

## 主要功能模块

- **用户认证与角色分流**：游客与管理员统一登录，JWT 鉴权；管理中台仅 admin 可进
- **门票大厅**：按分类、价格、推荐筛选已上架票种，查看封面、现价/原价、权益与预订须知
- **实名下单支付**：选择游玩日期与数量，填写出游人信息，账户余额支付后生成 8 位核销码与二维码
- **我的订单**：待付款继续支付/取消，已支付查看核销码，符合规则可申请退款并回退余额
- **游乐设施与演艺**：按分区、刺激度、排队时长浏览设施，查看演艺场次与容量
- **公告指南与评价**：乐园公告、游园指南阅读，游客评价与管理端回复
- **个人中心**：资料维护、密码修改、演示范围内余额充值
- **经营驾驶舱**：订单量、营收、游客与票种 KPI，以及趋势/结构类 ECharts 图表
- **园区档案中台**：主题分区、游乐设施、演艺排期封面与开放信息维护
- **票种与履约**：票种分类/日库存/上下架，全量订单监管与退款处理
- **入园核销中心**：按核销码核验入园并登记核销记录
- **论文与 UML 概览**：配套论文设计实现页拼图与 UML 图列表，便于答辩材料对照

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E9%97%A8%E7%A5%A8%E5%A4%A7%E5%8E%85.png" alt="门票大厅" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E6%B8%B8%E4%B9%90%E8%AE%BE%E6%96%BD.png" alt="游乐设施" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E6%88%91%E7%9A%84%E8%AE%A2%E5%8D%95.png" alt="我的订单" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E7%AE%A1%E7%90%86%E5%91%98%E4%BB%AA%E8%A1%A8%E7%9B%98.png" alt="管理员仪表盘" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E7%A5%A8%E7%A7%8D%E7%AE%A1%E7%90%86.png" alt="票种管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E8%AE%A2%E5%8D%95%E7%AE%A1%E7%90%86.png" alt="订单管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/parkticket/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->
