# 镜头决策表（Camera Decision Tables）

> 本文件从 SKILL.md STEP 1-3 提取，供运行时按需加载。
> 包含：景别选择、运镜选择、机位角度与焦段三大决策表。

---

## STEP 1: 景别选择

### 七级景别与叙事功能

| 景别 | 英文 | 画面范围 | 叙事功能 | 情绪效果 | Prompt 关键词 |
|------|------|---------|---------|---------|-------------|
| 大远景 | Extreme Wide Shot | 人物极小，环境占满 | 建立世界观/史诗感 | 渺小、壮阔、孤独 | `extreme wide shot, tiny figure in vast landscape` |
| 远景 | Wide Shot | 全身+大量环境 | 交代地点/空间关系 | 客观、冷静 | `wide shot, full body with surrounding environment` |
| 全景 | Full Shot | 完整全身 | 展示身体语言/服装 | 中性、介绍性 | `full shot, character from head to toe` |
| 中景 | Medium Shot | 腰部以上 | 对话/互动/动作 | 自然、亲近但有距离 | `medium shot, waist up` |
| 中近景 | Medium Close-up | 胸部以上 | 强调表情+保留手势 | 亲密感增加 | `medium close-up, chest and above` |
| 近景 | Close-up | 头部+肩 | 传递情绪/内心 | 强烈情绪投射 | `close-up on face` |
| 特写 | Extreme Close-up | 局部（眼/手/物） | 极端强调/细节揭示 | 紧张、聚焦、窥探 | `extreme close-up on [具体部位]` |

### 情绪 → 景别倾向

| 情绪 | 倾向景别 | 原因 |
|------|---------|------|
| 平静/日常 | 中景~中近景 | 自然对话距离 |
| 紧张/悬疑 | 近景~特写 + 偶尔远景 | 近景读表情 + 远景孤立角色 |
| 震撼/史诗 | 大远景~全景 | 展示规模 |
| 悲伤/绝望 | 近景(情绪) + 远景(孤独) | 交替使用最有效 |
| 温馨/亲密 | 中近景~近景 | 贴近但不侵入 |
| 愤怒/爆发 | 中景→近景急推 | 从可控到失控的过程 |
| 恐惧 | 特写(反应) + 远景(威胁源) | 主观+客观交替 |

---

## STEP 2: 运镜选择

### 运镜 × 情绪映射

| 运镜 | 英文 | 情绪效果 | 适用场景 | 速度参考 |
|------|------|---------|---------|---------|
| 缓推 | Slow Dolly In | 引导聚焦/逐步揭示 | 对话中发现真相、角色决心 | 3-5s 推至目标 |
| 急推 | Crash Zoom / Fast Push | 震惊/发现/强调 | 揭示关键信息、反转 | 0.5-1s |
| 缓拉 | Slow Pull Out | 揭示全貌/孤独/告别 | 结尾、离别、绝望 | 3-8s |
| 急拉 | Fast Pull Out | 震撼揭示/规模展示 | 军队出现、灾难规模 | 0.5-1.5s |
| 横移 | Dolly/Track Left/Right | 跟随/扫描/平行叙事 | 跟随行走、展示空间 | 匹配角色移速 |
| 环绕 | Arc Shot / Orbit | 戏剧性/仪式感/审视 | 英雄时刻、对峙、起誓 | 2-5s 半圈 |
| 升降 | Crane Up/Down | 权力转移/揭示/俯瞰 | 神化→揭真相、城市俯瞰 | 2-4s |
| 手持 | Handheld | 纪实/紧张/混乱 | 追逐、战斗、恐慌 | 不规则 |
| 固定 | Static / Locked | 客观/冷静/压迫(长镜) | 日常对话、审讯、等待 | N/A |
| 甩镜 | Whip Pan | 突然转换注意力 | 角色间快速切换、惊吓 | 0.2-0.5s |
| 变焦推拉 | Dolly Zoom / Vertigo | 空间扭曲/心理失衡 | 角色认知崩塌、恐惧 | 2-3s |

### 动作强度 → 运镜搭配

| 动作强度 | 推荐运镜 | 运镜占比 | 运镜速度 |
|---------|---------|---------|---------|
| 静态（对话/等待） | 固定为主 + 偶尔缓推 | 运镜 20%，固定 80% | 极慢 |
| 轻度（行走/日常） | 缓推/缓拉/横移跟随 | 运镜 40%，固定 60% | 慢~中 |
| 中度（争吵/奔跑） | 手持 + 横移 + 急推 | 运镜 60%，固定 40% | 中~快 |
| 激烈（打斗/追逐） | 手持 + 甩镜 + 急推急拉 | 运镜 80%，固定 20% | 快 + 速度变化 |

---

## STEP 3: 机位角度与焦段

### 角度 × 权力/情绪映射

| 角度 | 英文 | 权力信号 | 情绪效果 | Prompt 片段 |
|------|------|---------|---------|------------|
| 平角 | Eye Level | 平等 | 客观、中性、共情 | `eye-level camera angle` |
| 微仰 | Slight Low Angle | 轻微崇敬 | 好感、信任 | `slightly low camera angle, looking up 10°` |
| 仰拍 | Low Angle | 被摄者强大 | 威严、英雄、压迫 | `low angle shot, looking up at character, imposing` |
| 微俯 | Slight High Angle | 轻微弱势 | 脆弱、可爱、同情 | `slightly high angle, looking down 10°` |
| 俯拍 | High Angle | 被摄者渺小 | 脆弱、被困、绝望 | `high angle shot, looking down, character appears small` |
| 鸟瞰 | Bird's Eye / Top-down | 上帝视角 | 全知、宿命、疏离 | `bird's eye view, directly overhead` |
| 荷兰角 | Dutch Angle | 失衡 | 不安、疯狂、混乱 | `Dutch angle, tilted horizon 15-30°` |

### 焦段 × 空间感映射

| 焦段范围 | 空间效果 | 情绪效果 | 适用场景 | Prompt 片段 |
|---------|---------|---------|---------|------------|
| 14-24mm 超广角 | 空间夸张拉伸 | 壮阔/扭曲/压迫 | 史诗全景、密闭空间恐惧 | `ultra wide-angle 16mm lens, exaggerated perspective` |
| 24-35mm 广角 | 空间宽敞自然 | 开放/纪实/日常 | 环境交代、纪实风格 | `wide-angle 28mm lens, natural spatial depth` |
| 35-50mm 标准 | 接近人眼视角 | 客观/真实/平衡 | 通用叙事、对话 | `standard 50mm lens, natural perspective` |
| 85-135mm 中长焦 | 压缩空间、虚化背景 | 亲密/隔离/聚焦 | 人像、情感特写 | `85mm telephoto, shallow depth of field, background blur` |
| 200mm+ 长焦 | 极度压缩、窥视感 | 偷窥/监视/疏离 | 跟踪、偷拍视角 | `200mm telephoto, compressed perspective, voyeuristic` |

### 构图速选

| 构图法则 | 适用场景 | Prompt 片段 |
|---------|---------|------------|
| 三分法 | 通用默认，人物偏左/右三分线 | `rule of thirds composition, subject on the left third` |
| 中心构图 | 对称仪式感、英雄独白、BOSS 出场 | `centered composition, symmetrical framing` |
| 对角线构图 | 动态感、动作方向引导 | `diagonal composition, dynamic leading lines` |
| 前景遮挡 | 偷窥感、层次感、悬疑 | `foreground framing, shooting through [obstacle]` |
| 留白构图 | 孤独、渺小、压迫、极简 | `negative space composition, vast empty area around subject` |
