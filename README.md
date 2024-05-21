﻿# 停车场收费统计管理系统前端项目
## 项目简介
**本项目修改自开源项目**[PanJiaChen-vue-admin-template](https://github.com/PanJiaChen/vue-admin-template)

本项目采用B/S架构，前端使用Vue.js 2.6框架搭配Element UI组件库，后端[parking-system-nodejs](https://github.com/Jokul482/parking-system-nodejs)则依托Node.js及Express技术栈，实现了一个全面覆盖车辆进出管理、车位信息管理、收费统计与用户权限控制的综合性平台。本项目旨在为学生、开发者提供一个实践Node.js、Vue.js及全栈开发技能的学习样本。
## 功能特性
### 核心功能
- **车辆进出管理**：支持车辆登记、出场结算信息处理，实现车辆信息的快速录入、查询与维护，优化车辆流动效率。
- **车位信息管理**：提供车位查询、数据统计与维护功能，帮助管理者实时掌握车位状态，有效调度资源。
- **收费统计**：实现停车费用统计、车流量分析，支持数据导出，助力财务分析与运营决策。
- **用户管理**：集成菜单权限控制系统，支持用户账户的增删改查，确保系统安全性与操作便捷性。
### 技术栈
- **前端**：Vue.js 2.6 + Element UI，实现响应式、组件化的用户界面。
- **后端**：Node.js + Express，构建高效、可扩展的服务端逻辑。
- **数据库**：MySQL，存储与管理所有业务数据。
- **开发工具**：Visual Studio Code，提供高效编码与调试环境。
### 特色亮点
- **渐进式框架**：Vue.js的渐进式设计，让系统易于上手且可逐步迭代。
- **组件化开发**：Element UI组件库，加速界面构建，提升开发效率。
- **事件驱动服务端**：Node.js事件驱动架构，保证高性能、低延迟的后台服务。
- **B/S架构**：简化部署，用户只需浏览器即可使用，降低使用成本。
## 安装与运行
1. 环境准备：Node.js、MySQL及其前端项目环境
2. 克隆代码：git clone项目地址`
3. 依赖：npm install
4. 配置数据库：参见后台项目中.sql文件及db文件夹
5. 启动：npm run dev
## 注意事项
- **学习交流**：本项目适合Node.js、Vue.js初学者及全栈开发爱好者学习交流。
- **非生产环境**：作为教学演示项目，不推荐直接部署于生产环境，请自行评估安全与稳定性需求。
