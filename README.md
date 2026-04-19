# Muthur Command audio plugin (PulseAudio)

中文文档: [`README.zh-CN.md`](./README.zh-CN.md)

Supervisor-managed **audio** add-on for **Muthur Command OS** (PulseAudio on **`ghcr.io/muthur-command/base`**; OCI labels **`io.mcio.*`**).

Upstream ALSA card configs are retained where applicable; see **LICENSE** for copyright.

## Operations

If your stack exposes the Supervisor CLI, **`mc audio`** commands remain useful for inspection and control (legacy stacks may still expose **`ha audio`**); see **Muthur Command OS** / Supervisor documentation for exact behavior.

## Origin

- **Upstream:** [home-assistant/plugin-audio](https://github.com/home-assistant/plugin-audio) — Home Assistant Supervisor audio (PulseAudio) plugin container, from which this tree was ported.
- **In this repo:** **Muthur Command** keeps this fork for **Muthur Command OS**; behavior may diverge from upstream over time.
- **License:** Code inherited from upstream remains **Apache-2.0**; see **LICENSE** (retain upstream copyright / NOTICE where required).
