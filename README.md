# 紫页 · Markdown 阅读主题

两种配色，每种只有一个独立 CSS 文件。适用于 **Typora、VS Code MPE 和普通 Markdown 网页**，无需安装依赖或运行网站。

| 主题 | 文件 |
| --- | --- |
| 紫笺 · 柔和紫色 | [purple-notes.css](purple-notes.css) |
| 鲸蓝 · 清透蓝色 | [blue-notes.css](blue-notes.css) |

## 安装

- **Typora**：打开「偏好设置 → 外观 → 打开主题文件夹」，放入选中的 CSS，重启后选择 **Purple Notes** 或 **Blue Notes**。
- **MPE**：在 VS Code 运行 `Markdown Preview Enhanced: Customize CSS`，备份后将所选 CSS 的完整内容粘贴进打开的 `style.less`，保存并刷新预览。CSS 可直接用于 LESS，无需另一个文件。
- **网页**：引入所选 CSS，为渲染后的正文容器添加 `class="markdown-body"`。

只启用其中一种配色。字体、颜色、行距等参数可以直接修改 CSS 开头的共享规则；编辑器负责 Markdown、公式与图表的解析。不同编辑器的编辑界面和扩展语法以实际效果为准。

## 致谢

配色与阅读排版参考 [typora-purple-theme](https://github.com/hliu202/typora-purple-theme)，README 结构参考 [Konayuki](https://github.com/aerandirsf/Konayuki)。样式独立实现，采用 [MIT](LICENSE) 许可。

本仓库仅发布主题 CSS，不包含在线定制工坊或角色插画。
