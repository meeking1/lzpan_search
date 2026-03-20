# 网盘搜索导航


## 📋 项目简介

这是网盘搜索导航的源码.  
**Demo**: [https://so.lzpanx.com](https://so.lzpanx.com)

## 🚀 网盘搜索网站搭建指南

### 免费程序：使用 PanSearch

- **下载地址**: [https://github.com/Xwudao/go-pansearch-release](https://github.com/Xwudao/go-pansearch-release)
- **文档**: [https://docs.hunhepan.com/pansearch/](https://docs.hunhepan.com/pansearch/)
- **说明**: PanSearch 是 ReMan 的免费版本，SEO 友好，功能简单。

### 收费程序：使用 ReMan

支持导入夸克、百度、迅雷网盘资源的搜索引擎源码.

#### 简介

ReMan 是一款拥有后台的个人网盘资源管理程序，帮助管理、搜索网盘资源.

#### 特点

- ✅ 完善的后台管理（资源、分类、用户、卡密等）
- ✅ 支持手机端和电脑端
- ✅ 程序文件：`config.yml` 和 `reman`（二进制文件，无源码）

#### 特色功能

- 📂 支持分类展示资源列表
- 🔝 设置资源为“自己的”以优先排序（有助于网盘拉新）
- 🆕 **2024/05/12 更新**: 添加用户系统 + 卡密系统
- 🔥 提供热词、热门资源记录，可在后台查看搜索热词
- 更多功能请体验演示：[https://docs.hunhepan.com/reman/](https://docs.hunhepan.com/reman/)

## 🔍 懒盘搜索

**Demo**: [http://so.lzpanx.com](http://so.lzpanx.com)

## 🛠️ 本地使用指南

### 环境准备

1. 安装 Node.js: [https://nodejs.org/en/](https://nodejs.org/en/)
2. 验证安装: 在终端运行 `node -v` 和 `npm -v`
3. 安装 Git: 用于克隆项目

### 步骤

1. **克隆项目**:

   ```bash
   git clone https://github.com/Xwudao/lzpan_search.git
   ```

2. **安装依赖**:

   ```bash
   npx pnpm i
   # 或
   npm i
   ```

3. **修改内容** (可选):
   - 编辑 `src/data/data.json` 以更新网站数据
   - 修改 `public/index.html` 或 `mobile.html` 中的标题等信息

4. **构建项目**:

   ```bash
   npm run build
   ```

5. **部署**:
   - 构建后生成 `dist` 目录
   - 将 `dist` 中的文件复制到网站根目录

## 🙏 感谢

本项目 CDN 加速及安全防护由 [Tencent EdgeOne](https://edgeone.ai/zh?from=github) 赞助

![Tencent EdgeOne](/images/tc.png)

## 📄 协议

MIT


[![Star History Chart](https://api.star-history.com/svg?repos=Xwudao/lzpan_search&type=Date)](https://star-history.com/#Xwudao/lzpan_search&Date)
