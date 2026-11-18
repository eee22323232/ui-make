# ui-make

一个用于 Web、桌面软件和移动 App 的 Codex 技能。它把开发者的 UI 描述转成可反馈的组件样例，再沿用项目技术栈实现和验证。

## 安装

将 `skills/ui-make` 整个目录复制到 `~/.agents/skills/`（供所有项目使用），或放到项目的 `.agents/skills/`（仅供该项目使用）。安装后，技能入口应位于目标目录下的 `ui-make/SKILL.md`。若技能列表未刷新，重启 Codex。

## 使用

在 Codex 里明确调用，例如「`$ui-make`，把通知设置页做得更紧凑，让我一眼看到还有哪些通知可以开启。」也可以直接说「我要做一个 UI」，由 Codex 按任务匹配技能。

关键设计会先给出精简组件代码，有条件时附上可运行预览，并请你确认一个会影响实现的问题。收到反馈后，技能会修订样例并落实到项目。明确的小改动直接实现。改版后在相同条件下检查易辨性、美观性和简洁性。

技能也会在需要时调查指定风格、核实图片和纹理的商用许可，或调用环境中已具备的相关工程技能。 [查看完整技能](skills/ui-make/SKILL.md) · [Skills for Real Engineers](https://github.com/mattpocock/skills#reference)
