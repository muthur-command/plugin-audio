# Muthur Command 音频插件（PulseAudio）

英文文档: [`README.md`](./README.md)

由 Supervisor 管理的 **音频** 插件容器，面向 **Muthur Command OS**（基于 **`ghcr.io/muthur-command/base`**；OCI 标签 **`io.mcos.*`**）。

在适用场景下保留上游 ALSA 声卡配置；版权见 **LICENSE**。

## 运维

若监管栈暴露 Supervisor CLI，使用 **`mc audio`** 系列命令进行查看与控制；具体以 **Muthur Command OS** / Supervisor 文档为准。

## 来源

- **上游：** [home-assistant/plugin-audio](https://github.com/home-assistant/plugin-audio) — Home Assistant Supervisor 的音频（PulseAudio）插件容器，本仓库由其移植而来。
- **本仓库：** **Muthur Command** 维护此 fork，供 **Muthur Command OS** 使用；行为可能随时间与上游产生差异。
- **许可：** 自上游继承的代码仍为 **Apache-2.0**；详见 **LICENSE**（按 fork 要求保留上游版权 / NOTICE）。
