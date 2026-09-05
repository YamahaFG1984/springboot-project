# 在线商店 · 教学文档

三份自包含的 HTML 教学文档，用同一个「在线商店」项目，把两套截然不同的技术栈
从零讲到生产。直接用浏览器打开即可，无需构建、无外部依赖。

## Spring Boot 线

| 文件 | 内容 | 篇幅 |
| --- | --- | --- |
| [`docs/springboot-store.html`](docs/springboot-store.html) | **第一季**：从 `main` 方法到可部署的 MVC 应用 | 序 + 13 部分 + 附录，12 张图，38 道思考题 |
| [`docs/springboot-store-advanced.html`](docs/springboot-store-advanced.html) | **第二季 · 进阶**：Redis、状态机、异步与外部依赖、可观测性 | 序 + 13 部分 + 附录，14 张图，39 道思考题 |

Spring Boot 4 / Spring Framework 7 / Jakarta EE 11 / Java 21+ ·
Thymeleaf 3.1 · Spring Data JPA + Hibernate 7 · PostgreSQL + Flyway ·
Spring Security 7 · Spring Modulith · Redis · Testcontainers · Micrometer

## Hono 线

| 文件 | 内容 | 篇幅 |
| --- | --- | --- |
| [`docs/hono-store.html`](docs/hono-store.html) | 同一个商店，换到光谱的另一端：没有容器、没有反射、没有装饰器 | 序 + 14 部分 + 附录，15 张图，42 道思考题 |

Hono 4 / TypeScript 5 strict / Node.js 22 · hono/jsx SSR · Drizzle ORM + drizzle-kit ·
PostgreSQL 17 · Zod 4 · argon2id · Biome · dependency-cruiser · Vitest + Testcontainers

两条线章节一一对应，附录里有 Nest / Spring Boot / Hono 的三栈术语对照表。
对照着读，最能分清哪些是框架的选择，哪些是问题本身的形状。

## 每一部分的结构

1. 它解决什么问题
2. 最小可用代码
3. 机制拆解（配图）
4. 常见错误做法 —— 包括原书（*Practical Nest.js*）在同一主题上的处理
5. 思考题，附可折叠的思路提示

## 关于原书

内容脉络取自 *Practical Nest.js: Develop clean MVC web applications*
（Correa & Lim, 2022），技术栈整体替换，并针对各自语言生态的实际情况做了加深。
原书没有事务、没有并发控制、没有 N+1、没有测试，`synchronize: true` 直接对着
生产库跑 —— 这些缺口在两条线里都补上了。

原书 PDF 属版权材料，不包含在本仓库中。
