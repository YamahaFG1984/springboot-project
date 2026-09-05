# Spring Boot 4 在线商店 · 教学文档

两份自包含的 HTML 教学文档，用一个「在线商店」项目把 Spring Boot 4 从零讲到生产。
直接用浏览器打开即可，无需构建、无外部依赖。

| 文件 | 内容 | 篇幅 |
| --- | --- | --- |
| [`springboot-store.html`](springboot-store.html) | **第一季**：从 `main` 方法到可部署的 MVC 应用 | 序 + 13 部分 + 附录，12 张图，38 道思考题 |
| [`springboot-store-advanced.html`](springboot-store-advanced.html) | **第二季 · 进阶**：Redis、状态机、异步与外部依赖、可观测性 | 序 + 13 部分 + 附录，14 张图，39 道思考题 |

两份文档共用同一套 `com.example.store` 代码库与设计系统，可按顺序阅读，文末互相链接。

## 技术栈

Spring Boot 4 / Spring Framework 7 / Jakarta EE 11 / Java 21+ ·
Thymeleaf 3.1 · Spring Data JPA + Hibernate 7 · PostgreSQL + Flyway ·
Spring Security 7 · Spring Modulith · Redis · Testcontainers · Micrometer

## 每一部分的结构

1. 它解决什么问题
2. 最小可用代码
3. 机制拆解（配图）
4. 常见错误做法 —— 包括原书（*Practical Nest.js*）在同一主题上的处理
5. 思考题，附可折叠的思路提示

## 关于原书

内容脉络取自 *Practical Nest.js: Develop clean MVC web applications*，
但技术栈整体替换为 Spring Boot 4，并针对 Java / Spring 的实际情况做了加深。
原书 PDF 属版权材料，不包含在本仓库中。
