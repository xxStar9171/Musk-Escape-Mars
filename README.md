# Musk Escape Mars

Musk Escape Mars 是一个使用 **Codex + Unity 6** 协作完成的第三人称科幻游戏原型。

这个项目的重点不是做一个完整商业游戏，而是探索 AI 编程工具如何辅助 Unity 游戏原型开发。通过自然语言描述需求，Codex 参与了项目结构搭建、C# 脚本生成、场景对象创建、HUD UI、粒子效果、交互逻辑和任务闭环设计。

## Project Overview

Musk Escape Mars is an experimental third-person sci-fi game prototype built with **Codex and Unity 6**.

The goal of this project is to explore how AI coding tools can help non-professional developers quickly turn an idea into a playable Unity prototype. Codex was used to assist with project structure, C# scripts, scene objects, UI, particle effects, and gameplay logic.

This is a prototype demo, not a polished commercial game.

## Game Concept

玩家扮演一名被困火星的探索者，需要在火星沙漠遗迹与人类前哨基地之间完成逃生任务。

游戏包含以下核心元素：

- 第三人称角色控制
- 火星沙漠开放场景
- 能量核心收集任务
- 倒计时压力
- 外星生物敌人
- 星舰发射逃离结局
- HUD 任务界面
- 粒子、烟雾、喷焰等视觉反馈

## Controls

| Action | Key / Input |
|---|---|
| Move | `W` `A` `S` `D` |
| Sprint | `Left Shift` |
| Jump | `Space` |
| Camera Control | Mouse Movement |
| Attack / Interact with enemy | Mouse Button or `F` |
| Interact / Launch Starship | `E` |
| Collect Energy Core | Walk close to the core |
| Exit Play Mode | `Esc` or Unity Editor Stop Button |

## Gameplay Flow

1. 玩家进入火星场景。
2. HUD 显示时间、核心数量和当前目标。
3. 玩家需要在限定时间内寻找并收集能量核心。
4. 场景中存在外星生物和环境压力。
5. 收集完成后，玩家返回星舰发射平台。
6. 按下 `E` 启动星舰。
7. 星舰点火、喷烟、升空，任务完成。

## Development Notes

这个 Demo 主要通过自然语言与 Codex 协作完成。开发过程中，Codex 辅助完成了：

- Unity 项目结构搭建
- C# 脚本生成
- 第三人称角色控制
- 摄像机跟随逻辑
- 能量核心收集系统
- 倒计时系统
- 敌人交互逻辑
- HUD UI 显示
- 星舰发射动画
- 粒子效果与场景反馈
- 基础关卡对象搭建

Unity 本身包含场景层级、组件系统、材质、碰撞、动画、UI、输入系统和打包设置等复杂流程。这个项目尝试验证：AI 能否帮助零基础或非专业开发者降低学习门槛，更快完成一个可运行、可交互、可继续迭代的游戏原型。

## Tech Stack

- Unity 6
- C#
- Codex
- AI-assisted prototyping workflow

## Status

Current status: **Prototype Demo**

This project is still experimental. It is intended for learning, testing, and demonstrating an AI-assisted game development workflow.

## Disclaimer

This project is a fan-made experimental prototype for AI-assisted development research and learning purposes only. It is not affiliated with Unity, OpenAI, SpaceX, Tesla, or Elon Musk.
