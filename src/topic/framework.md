# `Supabase` & `Vercel`

Web 应用：

+ 资源服务，用 `Next.js`
+ 后端服务，用 Python / JS + `Supabase`
+ 前端部署：`Vercel`
+ 后端部署：`Docker`

## 1. `Supabase`

`Supabase` 开源的 Firebase 替代品，后端及服务（`BaaS`，Backend as a Service）平台

提供 服务器端 的 功能：

+ 数据库：`PostgreSQL`
+ `Auth`：用户认证（账号密码，邮箱，Github 等）
+ 实施订阅：`WebSocket` 实时数据同步
+ 存储：对象存储服务，文件 上传，下载
+ 边缘函数：边缘节点上运行js函数；处理请求 / 触发事件

## 2. `Vercel` & `Next.js`

`Jamstack` 动态生成的内容 显示在 静态交付的网站上，例如从静态托管或 CDN（内容交付网络）提供 HTML。首字母缩略词 `JAM` 代表网页的组件： Javascript、APIs 和 Markup；流程：Client -- CDN -- FaaS API

`Vercel`：开发、预览 和 部署 Web应用 的 云平台；为前端和全站开发者服务；适合部署`JAMstack`架构应用

主要解决：

+ 简化 部署流程：将代码库连接到平台进行自动部署；
+ 实时预览：每次提交，自动创建实时预览；
+ 边缘网络：Vercel具有全球CDN，进行内容分发；

Next.js: Vercel团队维护的，Node的开源React前端框架

提供了 预渲染、服务器渲染、静态生成 等

Next.js主要解决：

+ 服务器渲染 / 静态生成，改善SEO（搜索引擎优化）
+ 预渲染：预渲染页面可以在服务器上生成HTML
+ 页面路由
+ API路由: 在pages/api目录下创建API路由
+ 快速刷新: 支持React Fast Refresh

## 3. `Serverless` 无服务器框架

`FaaS`：函数即服务，Function as a Service，都是 Serverless 函数 平台 提供的功能，底层 依赖于 `BaaS`；

减少 部署 & 运维 成本，专注 开发构建应用。

不需要担心服务器的 规模、性能、安全性、可用性 等问题。

+ 冷启动问题：函数需要在请求到达时才启动，导致性能问题，目前都已经得到改进。
+ 成本：按使用量计费，而不是预先分配资源；如果有很大的流量波动或长时间空闲，就很划算。
+ 控制权和可移植性：担心依赖某个平台；但是，有很多工具和技术可以解决这类问题，比如 `Kubernetes` 和 `OpenFaaS`。

## 4. 边缘函数 `Edge Compute`

优化云计算系统 性能 的 方法，将数据处理任务 靠近 数据源的地方 执行，从而减少延迟和带宽使用。

对于实时应用（游戏、流媒体服务、物联网设备 等）非常有用。

+ 类似 `CDN` 在 资源下载 的地位
+ 目的：减少物理距离，降低 延迟；

支持平台：

+ `AWS Lambda`
+ Google Cloud
+ Microsoft Azure Function
+ `Cloudflare` Workers 全球CDN网络 部署 和 复制
+ `Vercel`边缘功能，聚焦在 前端开发 和 JAMstack 架构
+ `Netlify Edge`: Deno提供，静态网站托管 和 部署
+ `Supabase Functions`: 用Deno构建
+ 阿里 Link IoT Edge

框架：

+ Vercel `Next.js`，支持Vercel边缘功能，Netlify的边缘功能
+ Deno 部署 能 在边缘 即时部署 TS/JS/Wasm 代码
    - Supabase Function 和 Netlify Edge 是用 Deno 构建的。

## 5. `BaaS` 和 `CMS` 区别

CMS（Content Management System）内容管理系统，比如：WordPress

+ 内容创建
+ 内容存储
+ 工作流管理
+ 发布

区别：

+ `CMS` 专注于 内容管理；
+ `BaaS` 专注于 后端功能，让开发人员专注前端；