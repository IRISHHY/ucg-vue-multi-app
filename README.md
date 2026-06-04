# Homediary · 家居社区 Web 端

## 介绍
本项目是基于 uni-app + uniCloud 开发的**家居社区 UGC 多端项目**，属于个人学习实战作品。项目涵盖内容浏览、用户发帖互动、团购活动、招聘资讯等完整社区模块，支持 H5 移动端与多端适配。

项目原依赖 uniCloud 云服务与 Node.js 后端，目前云端环境已停用，仓库保留完整前端源码，并内置本地 Mock 数据降级方案，可直接本地运行演示界面与完整业务逻辑。管理后台因包含敏感配置，暂未开源。

### 功能概览
- 首页图文信息流、社区内容浏览
- 用户发帖、点赞、评论、收藏等 UGC 互动功能
- 团购活动、家居招聘合作页面模块
- 用户注册、登录、个人中心完整权限流程

### 技术栈
- 前端：uni-app（Vue3）、uni-ui、uv-ui
- 原云后端：uniCloud 支付宝云（现已停用归档）
- 历史后端：Express + MongoDB（旧版归档代码，仅作学习参考，不再使用）

### 本地运行方式
无需联网后端，项目内置 Mock 数据降级逻辑，请求失败自动切换本地演示，可直接通过 HBuilderX 运行到浏览器查看完整界面效果。

### 项目说明（学习作品 · 2025.5）
本项目是我零基础自学编程阶段完成的完整实战项目，无系统专业培训，依靠官方文档、教程与反复调试完成开发，并曾成功上线部署、跑通全部核心业务流程。

- **初期问题**：项目初期采用前端优先的开发模式，作为零基础自学开发者，缺乏架构思维，导致页面、接口、数据逻辑未严格解耦，代码规范性不足，修改功能易引发连锁问题，开发效率较低。
- **技术复盘**：项目完成后系统学习软件架构知识，深刻理解了分层设计、代码解耦、前后端职责边界的核心意义，纠正了初期无序开发的问题。
- **流程优化**：迭代出标准化开发流程，转变为后端先行的开发模式，优先完成数据模型、接口、权限的整体设计，再进行前端开发，大幅提升项目稳定性与开发效率。
- **技术拓展**：自主学习Python技术，搭建系统化的开发、调试、联调体系，补齐自身技术短板。

### 界面预览
<img width="320" alt="H5首页截图" src="https://github.com/user-attachments/assets/a593057b-def0-46e5-b393-6cf2e77c5a0e" />

---
# Homediary · Home Living Community | Cross-platform UCG Project

## Introduction
This is a personal learning and practical project, a home furnishing UGC community developed with uni-app and uniCloud. It supports multi-terminal adaptation, including H5 mobile web. The project covers complete community functions such as content browsing, user posting, liking, commenting, group buying and recruitment information modules.

The original uniCloud cloud service and Node.js backend are no longer maintained. This repository reserves the complete frontend source code. Local mock data fallback is built in the project for offline demonstration. The admin backend is not open-sourced due to sensitive configuration.

### Features Overview
- Homepage graphic content stream and community content browsing
- Complete UGC interaction: user posting, liking, commenting and collecting
- Group buying activities and home furnishing recruitment modules
- User registration, login and personal center system

### Tech Stack
- Frontend: uni-app (Vue3), uni-ui, uv-ui
- Original cloud backend: uniCloud (Alipay Cloud, now deprecated)
- Legacy backend: Express + MongoDB (archived version, for reference only)

### Local Preview
No online server required. The project supports local mock data fallback. You can run the project in HBuilderX and preview all page functions directly in the browser.

### Project Background & Self-Reflection
This project was independently completed during my early self-learning period. Without systematic professional training, I learned through official documents and continuous trial and error, and successfully deployed the project online with complete available functions.

- **Early Development Problems**: Initially, I had limited technical knowledge and even struggled with basic CSS. Without systematic architecture or decoupling design, I built features directly from the frontend, tightly coupling styles, business logic, API calls, and data processing. This unstandardized code led to cascading bugs and high modification costs whenever I adjusted functionality or styles.
- **Technical Summary & Insights**: After completing the project, I systematically learned software architecture theories and deeply understood the importance of layered design, code decoupling and clear boundary division between frontend and backend.
- **Optimized Development Workflow**: I abandoned the disordered development mode and switched to a standardized backend-first workflow. I complete data model, API and permission design in advance before frontend development, which greatly improves project stability and development efficiency.
- **Capability Expansion**: To build comprehensive full-stack capabilities, I self-studied Python and established a systematic process for development, debugging and joint testing to make up for technical deficiencies.
