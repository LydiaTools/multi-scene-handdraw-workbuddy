---
name: multi-scene-handdraw-workbuddy
description: 使用可复现工程制作有字幕和配乐的多幕手绘沟通短片。包含真实逐笔渲染器、四幅原创插画与已验证案例，可供WorkBuddy或Codex加载。
---

# 多幕手绘故事入口

本仓库的完整Skill与素材在同目录`multi-scene-story-workbuddy.zip`中。先用Python标准库zipfile将其解压到本次独立任务目录，再读取解压后的`multi-scene-story-workbuddy/SKILL.md`，执行其中流程。不要只读取这个入口而遗漏素材。

用户只需给主题，Agent负责计划与执行。本包已实测的直接复现主题是“为什么你越劝，别人越不听”。新主题需要Agent重新规划故事、生成适合的插画和授权音轨；没有这些能力时保留已完成内容并说明缺项，不能只换标题冒充新作品。

不要在Skill原目录生产项目，不使用preview.mp4冒充重新渲染结果，不把Codex制作工程描述为WorkBuddy独立创作。
