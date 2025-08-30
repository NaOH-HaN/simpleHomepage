# simpleHomepage Template

GitHub个人(信息)主页示例模板
GitHub Personal (Profile) Home Page Example Template

## 预览 | Preview

![preview][file.preview]

## 主要结构 | Main Struct

- **顶部导航栏**：锚点导航，移动端自动收起为汉堡菜单。

- **头图（Hero）区块**：展示头像、姓名、一句话简介和主要行动按钮（如查看项目、联系方式、GitHub）。

- **关于我**：简要介绍个人背景、当前关注方向和期望机会。

- **技能栈**：以列表形式展示前端、后端、工具、设计等技能。

- **项目展示**：以卡片形式展示代表性项目，可填写项目名称、简介和访问链接。

- **时间线**：以时间轴方式展示重要经历或里程碑。

- **联系方式**：列出常用社交账号和邮箱

- **页脚**：版权信息

## 快速开始 | Getting Start

### 克隆或复制模板
- 直接复制 `index.html` 文件到你的仓库或本地项目目录下。

- 推荐将本项目部署到 GitHub Pages，仓库名建议为 `<你的用户名>.github.io`。

### 自定义内容
将文档内的示例信息替换为你的个人信息，它们具体是：

- 替换头像图片：将你的头像图片命名为 `avatar.jpg`，放入 `assets/` 文件夹。

- 修改头图信息：在 `<header class="hero">` 区块修改姓名、简介、按钮链接等。

- 编辑“关于我”、“技能栈”、“项目”、“时间线”、“联系方式”等区块内容，填写你的真实信息。

- 项目卡片可根据实际项目数量增删 `<article class="project">` 元素。

- 联系方式区块可添加或删除社交媒体链接。

##### 自定义样式
- 可在 `<style>` 标签内调整主题色、背景图片、圆角、阴影等变量。

- 支持浅色/深色模式自动切换，也可根据需要调整配色方案。

#### 进阶用法
- 如需添加更多区块或自定义动画，可参考现有结构扩展 HTML 和 CSS。

- 所有交互逻辑均在底部 `<script>` 标签内实现，可根据需要修改或扩展。

## [许可协议 | License][file.license]

基于 MIT 许可证开源，可自由修改和分发，© NaOH_HaN 2025

Licensed under the MIT License. © NaOH_HaN 2025


[file.preview]: assets/preview.png
[file.license]: LICENSE