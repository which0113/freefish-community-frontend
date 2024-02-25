<p align="center">
    <img src=https://img.freefish.love/logo.png width=188/>
</p>
<h1 align="center">FreeFish-咸鱼社区</h1>
<p align="center"><strong>咸鱼社区是一个类似掘金的技术社区</strong></p>

## 项目介绍

本项目类似一个简版的掘金这样的技术社区，实现了多个用户注册，登录，发帖，评论，关注，搜索等功能。

## 环境准备

安装 `node_modules`:

```bash
npm install
```

or

```bash
yarn
```

## 提供的脚本

### 启动项目

```bash
npm run serve
```

### 构建项目

```bash
npm run build
```

## 技术栈

- Spring Boot
- Spring MVC
- MySQL 数据库
- Spring Security （JWT 安全校验）
- Spring Boot Starter（SDK 开发）
- Swagger + Knife4j 接口文档
- ElasticSearch 全文搜索
- Redis 数据缓存
- Kibana + Canal （MySQL 和 ES 数据同步）
- MyBatis-Plus 及 MyBatis X 自动生成
- Hutool、Apache Common Utils、Gson 等工具库