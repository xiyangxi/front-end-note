# 前端项目架构设计
## 自我介绍

- 混合着前端发展历程，介绍自己做前端的经验以及做过的一些产品
- 技术博客
- 业余项目

## 架构设计的目标
在架构基础上

- 能实现需求
- 轻松上手 -> 学习成本
- 快速开发 -> 开发效率
- 性能优秀 -> 性能

在能实现需求的基础上，上面几点的权衡取舍。

## 具体步骤

- 技术选型
    - 能实现需求
        - 兼容指定浏览器
        - 设备
    - 学习成本
        - 概念的数量和难易程度
        - 学习文档；教程数量
    -  开发效率
        - 框架状态。成熟
        - 代码质量
            - 开发团队
            - 测试覆盖率
        - 社区（出了问题是否能容易的找到答案；或有人来回答）
        - 写法
        - 支持的特性
        - 第三组件的数量，质量
        - 是否方便调试
    - 性能
- 建一个示例项目来采坑。示例项目要包括要做的项目的一些典型功能。
    - 实现功能
    - 优化
- 帮助文档
    - 开发流程的文档
    - 代码示例

## 具体项目 Demo
https://github.com/iamjoel/admin-template

- 主要的技术框架： Vuejs 及相关组件 + Webpack + Sass + PostCss + ES6
    - 实现需求：
        - 兼容最新的 Chrome
        - PC，笔记本
    - 学习成本：可以接受
    - 开发效率
        - Vuejs
            - 模块化
            - 双向绑定
            - 单向数据流
            - Chrome 插件
            - 丰富的第三方库
        - Webpack
            - 编译各种资源
            - 项目打包
        - PostCss 的 AutoPrefix 免写前缀
- 示例项目。典型功能
    - 菜单
    - 面包屑
    - 多语言
    - 列表页
- 帮助文档