# Shaylee

AI Product / HRI / Embodied Interaction

我关注主动式 AI、桌面智能体、人机交互和智能硬件产品，喜欢把 product problem、interaction strategy 和 runnable prototype 放在同一条链路里验证。

## Featured Project

### [ZSY Desktop Companion](https://github.com/Shaylee03/zsy-desktop-companion)

**Active Desktop AI Companion Robot / 主动式桌面 AI 陪伴机器人**

An open-source portfolio prototype for people who study or work alone in front of a computer. The project explores how a small desktop robot can notice work rhythm, appear at the right moment, respond with low-pressure feedback, and gradually learn user preferences.

这个项目的出发点不是再做一个提醒工具，而是探索一个“懂节奏的桌面伙伴”：它通过本地桌面感知端整理电脑使用状态，由后端策略判断主动陪伴机会，再通过表情、字幕、轻动作或语音回应用户。

**What I built**

- Local desktop sensing side: foreground window, keyboard/mouse activity, AFK, system audio and ActivityWatch signals.
- Proactive strategy: `quiet / subtle / subtitle / speak` feedback levels based on state, risk, preference and robot availability.
- Memory mechanism: task context, user preference, behavior rhythm and interaction feedback.
- Hardware integration: connected an off-the-shelf ESP32-S3N16R8-EMOJI desktop robot kit to my own backend for expression, caption and motion feedback.

**Links**

- Portfolio: https://shaylee03.github.io/zsy-desktop-companion/
- Repository: https://github.com/Shaylee03/zsy-desktop-companion

## Focus Areas

- AI product strategy and proactive interaction design
- HRI: expression, motion, subtitle and voice feedback
- Desktop sensing and user-state modeling
- Personalization memory and feedback loops
- Smart hardware / embodied AI product prototypes
