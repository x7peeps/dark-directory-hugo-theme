# Dark Directory Hugo Theme

一个基于 `Hugo` + `Relearn` 的暗色目录主题扩展层，适合以下场景：

- 技术博客
- 知识库 / 文档站
- 产品宣传页
- 个人品牌官网

它不是从零重写的独立主题，而是在 `Relearn` 之上，通过 `layouts/`、`static/css/custom.css` 和 `static/js/custom.js` 提供一层更适合内容与产品共存的视觉和交互升级。

## 特点

- 暗色目录风格，适合长文、专题与知识库
- 左侧层级导航，适合多层内容组织
- 首页 Hero 强化，适合品牌站点
- 产品页宣传能力增强，适合展示截图、下载入口和产品说明
- 保留 Hugo Module 的轻量依赖方式，便于继续升级上游主题

## 目录结构

```text
.
├── archetypes/
├── content/
├── layouts/
├── static/
├── go.mod
└── hugo.toml
```

## 快速开始

1. 安装 Hugo Extended 与 Go。
2. 克隆本仓库：

```bash
git clone https://github.com/x7peeps/dark-directory-hugo-theme.git
cd dark-directory-hugo-theme
```

3. 拉取依赖并启动本地开发：

```bash
hugo mod tidy
hugo server
```

4. 打开本地地址：

```text
http://localhost:1313/
```

## 复用方式

你可以直接复用以下内容：

- `hugo.toml`
- `go.mod`
- `layouts/`
- `static/css/custom.css`
- `static/js/custom.js`

如果你已经有自己的 Hugo 内容仓库，也可以只挑选这些主题层文件进行合并。

## 依赖

- [Hugo](https://gohugo.io/)
- [Relearn Theme](https://github.com/McShelby/hugo-theme-relearn)

## 许可

本仓库使用 `MIT` 许可证。
