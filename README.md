# Skills 阅读与使用地图

面向 [mattpocock/skills](https://github.com/mattpocock/skills) 的中文阅读指南与完整实战。

在线打开：

https://tbk0ng.github.io/matt-doc/

## 这个页面包含

- 39 步完整阅读顺序
- 主链、on-ramp、维护回路和独立工具的 SVG 流程图
- 14 种场景的入口路线
- 27 个推广技能的全功能索引
- 一个具体项目 Course Video Manager 的完整开发实战
- 50 篇 AI 中文翻译，右侧浮窗直接阅读
- 阶段边界的五选项决策树
- 常见坑与第一次实操清单

## 页面结构

```text
index.html                页面本体
reading-guide-data.js     50 篇中文翻译数据
reading-guide-marked.js   Markdown 渲染器
```

无构建步骤，无外部 CDN。打开 `index.html` 即可离线阅读。

## 交互

- 点击左侧任意文档名，右侧浮窗载入中文翻译
- 拖动浮窗左边缘调整宽度
- `A−` / `A+` 调整字号
- `Esc` 或 `×` 关闭，底部按钮重新打开
- `#doc=docs/engineering/to-tickets.md` 形式的深链可以直接打开某篇
- 手机端自动变成全屏阅读页，表格支持横向滑动
- 手机返回键先关闭浮窗，再按一次才退出网页

## 翻译说明

中文翻译由 AI 生成，保留原 Markdown 结构、代码、命令、路径、链接和技能名。术语以英文原名为准。每篇翻译顶部都有“英文原文”链接，指向 mattpocock/skills 的 GitHub 页面。

## 致谢

- 原始技能与文档：[mattpocock/skills](https://github.com/mattpocock/skills)，MIT License
- Markdown 渲染：[marked](https://github.com/markedjs/marked)，MIT License
- 本项目内容基于上述仓库整理与翻译，不代表原作者对译文的认可
