<div align="center">

# 🎬 cinematic-camera-engine

## 12 类场景 × 8 种情绪 → 镜头方案自动出
## 12 scene types × 8 moods in, a shot-by-shot camera plan out.

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

电影级镜头语言自动决策引擎：输入场景描述、分镜或剧情文字，直接得到完整镜头方案——景别、运镜、机位角度、焦段、构图要点、叙事功能，以及可嵌入提示词的英文片段。它解决的不是「有哪些镜头」，而是「这个场景该用哪个镜头」：内置场景→镜头方案决策树，覆盖 12 种核心场景类型 × 8 种情绪基调，并附场景类型速判表。既支持单镜设计，也支持多镜头流（Shot Flow）编排，内置 8 套经典序列模板与景别跨级、运镜方向、轴线等衔接铁律。生成后静默自检 6 项，未通过自动修正再输出；多镜头项目还会指定色彩锚点，防止各镜头色温与饱和度乱跳。

### ✨ 能做什么

- 输入场景／分镜／剧情描述 → 输出景别＋运镜＋角度＋焦段＋构图＋叙事功能的完整方案
- 内置 12 种场景类型 × 8 种情绪基调决策树，附场景类型速判表
- 8 套经典镜头流模板：渐进揭示、情绪聚焦、震撼揭示、对话基础／升级、动作段落、孤独离别、群戏高潮
- 六条衔接铁律：相邻景别跨 ≥2 级、运镜不 180° 反向、轴线不越、快切段落后接长镜
- 生成后静默自检 6 项（景别跨级、运镜理由、角度与权力关系、单镜单任务、速度与情绪、连续同景别），未通过自动修正
- 跨镜头色彩锚点锁定，色彩描述强制量化（如 desaturated ~40%, teal-grey, Kodak Vision3 500T）

### 📦 包含的技能

- `cinematic-camera-engine` —— 见 [`cinematic-camera-engine/SKILL.md`](cinematic-camera-engine/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/cinematic-camera-engine.git
cp -r cinematic-camera-engine/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A cinematic camera decision engine: feed it a scene description, storyboard line, or plot beat and it returns a complete shot plan — shot scale, camera movement, angle, focal length, composition notes, narrative function, and an English prompt fragment for direct pasting. The problem it solves is not what shots exist but which shot this scene needs: it ships a scene-to-shot decision tree covering 12 core scene types × 8 emotional tones, plus a quick scene-type lookup table. It handles single shots and multi-shot flows, with eight classic sequence templates and hard transition rules for scale jumps, movement direction, and the 180° axis. Every plan is silently self-checked against six rules and auto-corrected, and multi-shot projects get a color anchor so temperature and saturation stop drifting between clips.

### ✨ What it does

- Scene, storyboard, or plot line in; full plan out with shot scale, movement, angle, focal length, composition, and narrative function
- Decision tree over 12 scene types × 8 emotional tones plus a quick scene-type lookup table
- Eight classic shot-flow templates: progressive reveal, emotional focus, shock reveal, dialogue, escalation, action, solitude, ensemble climax
- Six transition rules: jump at least two scale levels, no 180° reversals, keep the axis, land on a long shot after fast cuts
- Silent six-point self-check (scale jumps, movement motive, angle vs. power, one job per shot, speed vs. mood, repeated scales) with automatic correction
- Color-anchor locking with quantified grades such as desaturated ~40%, teal-grey, Kodak Vision3 500T

### 📦 Skills included

- `cinematic-camera-engine` — [`cinematic-camera-engine/SKILL.md`](cinematic-camera-engine/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/cinematic-camera-engine.git
cp -r cinematic-camera-engine/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
