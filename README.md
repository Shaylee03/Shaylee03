# Shaylee

我关注 AI 产品、人机交互和桌面智能体方向，喜欢把产品问题、交互策略和可运行原型放在同一条链路里验证。

## Featured Project

### 主动式桌面 AI 陪伴机器人

一个面向研究生和办公人群的个人产品原型。项目的出发点不是再做一个提醒工具，而是探索：

> 长时间坐在电脑前学习或工作时，AI 能不能像一个懂节奏的桌面伙伴一样，在合适的时候主动出现，用表情、字幕、轻动作或语音提供低压力陪伴，并随着使用逐步理解用户习惯？

当前原型串联了本地桌面 Agent、云端主动策略、个性化记忆和机器人硬件联调：

- 本地 Agent 采集前台窗口、键鼠活跃、AFK、系统音频和 ActivityWatch 等非摄像头桌面信号。
- 后端根据桌面上下文判断主动陪伴机会，并在 `quiet / subtle / subtitle / speak` 中选择反馈强度。
- 记忆机制记录任务上下文、用户偏好、行为节奏和交互反馈，让机器人逐步调整出现时机和表达方式。
- 基于 ESP32-S3N16R8-EMOJI 桌面机器人硬件与开源固件框架，完成自有后端接入、表情屏、底部字幕和动作反馈联调。

- Portfolio: https://shaylee03.github.io/zsy-desktop-companion/
- Repository: https://github.com/Shaylee03/zsy-desktop-companion

## Focus Areas

- AI 产品策略与主动式 Agent 体验
- 桌面上下文理解与用户状态建模
- HRI 交互策略：表情、动作、字幕、语音
- 个性化记忆与反馈闭环
- 智能硬件 / 具身智能产品原型
