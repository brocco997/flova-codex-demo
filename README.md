# Flova Codex Demo

Flova 创作与灵感首页、宿主对话内结果组件和项目审阅界面的交互原型。

在线预览：https://brocco997.github.io/flova-codex-demo/

## 演示内容

- 六张精选 Skill 卡片与 Skill 推荐入口
- 两列 16:9 作品灵感，分批加载 36 个示例
- Codex 风格的提示确认弹窗和直接输入入口
- 模拟创作对话、镜头候选、版本比较与项目审阅

本项目是独立的产品交互 Demo，使用本地示例数据，没有接入 OpenAI、MCP 或 Flova 后端。新增项目和草稿保存在当前浏览器的 localStorage 中。

## 本地预览

```sh
python3 -m http.server 8769
```

打开 http://localhost:8769/ 。页面不需要构建或安装依赖。

## 部署

GitHub Pages 从 `main` 分支根目录发布 `index.html`。
