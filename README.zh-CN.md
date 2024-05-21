# Tap4 AI Web UI
一个AI导航网站，提供快速访问顶级AI资源、工具和新闻。它具有分类链接、搜索功能和用户友好的界面，帮助用户高效地探索AI领域并及时了解最新进展。

[English](https://github.com/6677-ai/tap4-ai-webui/blob/main/README.md) | 简体中文

## 功能
- 国际化
- SEO友好（支持i18n）
- 动态 sitemap.xml（支持i18n）
- 快速发布
- 使用 NEXT 14 和 app 路由（react服务器组件）
- Supabase serverless 数据库

## 快速开始

### 在Vercel上部署 **（别忘了设置环境变量）**
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F6677-ai%2Ftap4-ai-webui.git&env=NEXT_PUBLIC_SITE_URL,GOOGLE_TRACKING_ID,GOOGLE_ADSENSE_URL,CONTACT_US_EMAIL,NEXT_PUBLIC_SUPABASE_URL,NEXT_PUBLIC_SUPABASE_ANON_KEY&project-name=tap4-ai)

## 本地运行
### 安装
- node
- nvm
- pnpm

### 设置
#### （1）克隆此项目
```sh
git clone https://github.com/6677-ai/tap4-ai-webui.git
```

#### （2）在supabase上注册一个账户，然后创建一个项目
[supabase](https://supabase.com/)

#### （3）设置环境变量
```sh
# 先运行此命令
# 然后填写相应的值
cp .env.example .env.local
```
#### （4）在开发模式下运行
切换到特定的node版本
```sh
nvm use
```
安装依赖包
```sh 
pnpm i 
```
在开发模式下运行
```sh
pnpm dev
```

## 我们产品的链接
### TAP4-AI-Directory
全球AI工具的集合。| 收集免费的ChatGPT镜像、替代品、prompt、其他AI工具等。欲了解更多信息，请访问：[Tap4 AI](https://tap4.ai)

### 如何在网站列表中获得您的首批用户
这是提交您的产品以获取用户的网站列表。请访问 [StartUp Your Product List](https://github.com/6677-ai/TAP4-AI-Directory/blob/main/Startup-Your-Product-List.md)
#### GPT-4o in OpenAI
2024.05.14发布的惊人新功能。GPT-4o来了，让我们与她聊天。请访问 [GPT-4o](https://openai.com/index/hello-gpt-4o/)

#### The Tattoo AI Generator and Design
Tattao AI Design是为纹身爱好者设计的纹身ai生成器。如果您对此感兴趣，请访问 [Tattoo AI Design](https://tattooai.design)

#### Anime Girl Studio -- AI Anime Girl Generator and Chat
Anime Girl Studio是AI anime girl生成器和聊天产品。您可以生成您喜欢的角色并与AI anime girl聊天，请访问 [Anime Girl Studio](https://animegirl.studio)

## 许可证
MIT