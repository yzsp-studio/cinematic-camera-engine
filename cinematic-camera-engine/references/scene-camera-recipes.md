# 场景→镜头方案配方表 — Scene Camera Recipes

12 种核心场景类型，每种给出**默认镜头方案 + 情绪变体 + AI Prompt 片段**。
STEP 0 决策树命中场景类型后，直接查本表获取完整方案。

---

## 1. 对话场景（Dialogue）

**触发词**：对话 / 聊天 / 争吵 / 告白 / 审讯 / 谈判 / 劝说

### 默认方案（日常对话）
| 要素 | 方案 |
|------|------|
| 建立镜头 | 双人中景（Medium Two-Shot），交代空间关系 |
| 主体交替 | 正反打（Shot-Reverse-Shot），中近景，过肩构图 |
| 情绪高点 | 插入近景/特写读反应 |
| 运镜 | 90% 固定，仅在情绪转折时缓推 |
| 角度 | 平角（Eye Level） |
| 焦段 | 50-85mm |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 温馨/亲密 | 正反打收紧至近景，焦段 85mm 强化虚化，暖色光 |
| 紧张/对峙 | 景别逐步从中景收至特写（随冲突升级），运镜加入微推，焦段 85-135mm |
| 争吵/爆发 | 手持微晃，中景快速收至近景，节奏加快，偶尔甩镜切换角色 |
| 审讯/压迫 | 审讯者仰拍 + 被审者俯拍，固定机位制造压迫感，特写穿插汗滴/手指 |
| 告白/深情 | 双人中景→缓推至单人近景，85mm 浅景深，背景柔化 |

### Prompt 片段（标准对话）
```
Medium two-shot of two characters facing each other at a café table, 50mm lens, eye-level, soft natural lighting. Cut to over-the-shoulder medium close-up of Character A speaking, 85mm lens, shallow depth of field.
```

---

## 2. 动作场景（Action）

**触发词**：打斗 / 追逐 / 逃跑 / 爆炸 / 战斗 / 飞车 / 格斗

### 默认方案
| 要素 | 方案 |
|------|------|
| 开场 | 全景建立空间和参与者 |
| 动作过程 | 中景~中近景捕捉动作，手持跟拍 |
| 冲击瞬间 | 特写捕捉打击点/爆炸/关键动作 |
| 结果 | 全景或中景展示结果/后果 |
| 运镜 | 手持为主 80%，甩镜切换角色，急推强调打击 |
| 角度 | 低角度增加力量感，混用平角和仰拍 |
| 焦段 | 24-50mm 广角捕捉动作幅度 |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 英雄式/热血 | 仰拍为主，升降运镜强化仪式感，慢动作特写打击瞬间 |
| 混乱/恐慌 | 手持极度不稳，荷兰角 15°，快切节奏（每镜头 < 2s） |
| 一对多 | 环绕镜头展示包围，主角低角度（仰拍=他更强） |
| 追逐 | 横移跟拍为主，Steadicam，速度感第一，偶尔 POV |

### Prompt 片段
```
Wide shot establishing a rain-soaked alley, two figures facing off, 28mm lens, low angle. Handheld medium shot tracking the first punch, camera shakes on impact. Extreme close-up of fist connecting with jaw, motion blur on impact, 35mm lens.
```

---

## 3. 内心戏（Inner Monologue）

**触发词**：独白 / 回忆 / 思考 / 凝视 / 犹豫 / 挣扎 / 下定决心

### 默认方案
| 要素 | 方案 |
|------|------|
| 主景别 | 近景~特写为主（读表情） |
| 辅景别 | 远景（角色在空间中的渺小/孤独感） |
| 运镜 | 极缓推近（3-5s），营造渐入内心的感觉 |
| 角度 | 平角或微俯（脆弱感） |
| 焦段 | 85-135mm，极浅景深，背景完全虚化 |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 回忆/怀念 | 柔焦效果，缓推从中景到近景，温暖色调 |
| 痛苦/挣扎 | 特写+荷兰角微倾（5-10°），手持轻微抖动 |
| 觉醒/下决心 | 从微俯缓变至平角→微仰（权力感上升），缓推至特写眼神 |
| 绝望/放弃 | 远景固定（人在空阔空间），极长持续（≥5s不切） |

### Prompt 片段
```
Close-up of character's face, 100mm lens, extremely shallow depth of field, background dissolved into warm bokeh. Slow dolly in over 4 seconds from medium close-up to tight close-up, ending on eyes glistening with unshed tears. Eye-level angle, minimal movement.
```

---

## 4. 角色入场（Character Entrance）

**触发词**：走进 / 到达 / 进入 / 来到 / 出现 / 推门 / 踏入

### 默认方案
| 要素 | 方案 |
|------|------|
| 序列 | 渐进揭示：远景（剪影/局部）→ 全景（完整身形）→ 中景（面部初现）→ 近景（记忆点特征） |
| 运镜 | 横移或缓推跟随，配合角色移动 |
| 角度 | 微仰（赋予好感/期待） |
| 焦段 | 远景 35mm → 近景 85mm 逐步收紧 |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 威严/BOSS | 从脚步特写→缓拉至全景，低角度仰拍，缓慢节奏 |
| 神秘/悬疑 | 剪影远景→局部特写（手/鞋）→ 最后才露脸，逆光 |
| 惊喜/欢乐 | 甩镜从其他角色的惊讶反应→切到入场者全景 |
| 日常/轻松 | 中景横移跟随走入，自然节奏 |

### Prompt 片段（威严入场）
```
Extreme close-up of polished black shoes stepping onto marble floor. Slow tilt up revealing tailored suit legs. Wide shot from low angle as the figure walks toward camera down a grand corridor, 24mm lens, imposing silhouette against backlight.
```

---

## 5. 环境展示（Environment Establishing）

**触发词**：城市 / 山脉 / 海洋 / 建筑 / 空间 / 房间 / 世界

### 默认方案
| 要素 | 方案 |
|------|------|
| 景别 | 大远景或远景 |
| 运镜 | 缓慢横移或升降（航拍感），2-5s |
| 角度 | 平角或鸟瞰 |
| 焦段 | 14-35mm 超广角~广角 |
| 持续 | ≥3s 让观众"读"空间 |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 壮阔/史诗 | 大远景 + 鸟瞰升降，14mm 超广角，黄金时段光线 |
| 压抑/末世 | 远景 + 高角度俯瞰，灰色调，固定机位长时间停留 |
| 温馨/家园 | 远景→缓推入中景（接近建筑/窗户），暖光 |
| 危险/未知 | 缓慢推入黑暗空间，手持微晃，广角形变制造不安 |

### Prompt 片段
```
Extreme wide shot of a sprawling cyberpunk city at dusk, 16mm ultra-wide lens, bird's eye view slowly panning right, neon lights reflecting on wet streets, dense vertical architecture fading into smog.
```

---

## 6. 角色首秀（Character Introduction）

**触发词**：第一次出现 / 亮相 / 登场 / 介绍角色

### 默认方案
| 要素 | 方案 |
|------|------|
| 序列 | 全景建立（角色在环境中的位置）→ 中景定位（体型/服装/气质）→ 特写记忆点（标志性特征：疤痕/饰品/眼神） |
| 运镜 | 全景固定 → 中景缓推 → 特写固定 |
| 角度 | 根据角色性格：英雄=微仰，反派=仰拍，普通人=平角 |
| 焦段 | 全景 35mm → 特写 100mm |

### 与"角色入场"的区别
- **角色入场** = 物理动作（走进来），强调空间运动
- **角色首秀** = 叙事事件（第一次让观众认识这个角色），强调特征记忆

### Prompt 片段
```
Full shot of a woman standing at the edge of a rooftop, 35mm lens, wind blowing her coat, city skyline behind. Cut to medium shot revealing her calm, scarred face, 50mm lens. Extreme close-up on her distinctive silver ring as she taps it against the railing, 100mm lens.
```

---

## 7. 告别 / 结局（Farewell / Ending）

**触发词**：分别 / 离开 / 结束 / 死亡 / 再见 / 最后一面

### 默认方案
| 要素 | 方案 |
|------|------|
| 序列 | 近景（捕捉最后的情绪）→ 缓拉至远景（人物在空间中缩小） |
| 运镜 | 缓拉（Slow Pull Out）3-8s，可叠加升降 |
| 角度 | 平角→过渡到微俯（旁观者视角） |
| 焦段 | 85mm（近景）→ 35mm（拉至远景） |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 悲痛/死亡 | 近景固定长镜（≥5s 不动），然后极缓拉远，无运镜让情绪沉浸 |
| 释然/平静 | 中景缓拉，配合角色转身离开的动作，自然光 |
| 不舍/留恋 | 双人中景→单人近景→缓拉至远景剪影 |
| 希望/新开始 | 缓拉至远景时角色走向光亮方向，微仰角 |

### Prompt 片段
```
Close-up of two hands slowly separating, 85mm lens, shallow depth of field. Slow pull out over 5 seconds revealing the character standing alone on an empty train platform, transitioning to wide shot, 35mm lens, the figure growing smaller as the camera retreats.
```

---

## 8. 揭示时刻（Revelation）

**触发词**：发现 / 揭示 / 真相 / 震惊 / 反转 / 原来如此

### 默认方案
| 要素 | 方案 |
|------|------|
| 序列 | 特写（角色反应/震惊表情）→ 急拉至远景/全景（揭示全貌） |
| 运镜 | 急拉（Fast Pull Out）0.5-1.5s，或 Dolly Zoom 2-3s |
| 角度 | 平角→根据揭示内容调整（威胁=仰拍，全貌=鸟瞰） |
| 焦段 | 特写 100mm → 全景 24mm 急切换 |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 震惊/恐惧 | Dolly Zoom（背景拉近+机位后退），荷兰角 |
| 感动/释然 | 缓拉（而非急拉），眼含泪光特写→温暖远景 |
| 惊喜 | 甩镜从角色反应→揭示对象，快速节奏 |
| 恐怖揭示 | 极缓推向揭示物，5s 以上，制造不安的等待感 |

### Prompt 片段（震惊型）
```
Extreme close-up of character's eyes widening in shock, 100mm lens, pupils dilating. Dolly zoom effect over 2 seconds as the background warps and stretches, creating vertigo sensation, the character's face remains in frame while the world distorts behind them.
```

---

## 9. 静态情绪（Static Emotion）

**触发词**：等待 / 孤独 / 无聊 / 寂寞 / 发呆 / 沉默 / 静坐

### 默认方案
| 要素 | 方案 |
|------|------|
| 主景别 | 远景（角色在大空间中显得渺小） |
| 辅景别 | 特写（局部：手指/嘴角/眼神）用于打破视觉单调 |
| 运镜 | 以固定为主（≥80%），强调静止和空旷 |
| 角度 | 平角或微俯 |
| 焦段 | 远景 28mm + 特写 100mm 交替 |
| 节奏 | 慢——每个镜头 ≥3s，让"空"本身成为表达 |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 等待/期盼 | 固定中景，角色视线朝向画面外（暗示等待的对象） |
| 孤独/被遗弃 | 大远景固定，角色极小，空间极大，持续≥5s |
| 麻木/倦怠 | 平角固定，无运镜，面部特写无表情变化 |
| 内心挣扎 | 固定近景长镜，微小的表情变化是唯一的动态 |

### Prompt 片段
```
Wide shot of a lone figure sitting on a park bench, 28mm lens, eye-level, vast empty park stretching behind, autumn leaves scattered, completely still frame held for 5 seconds. Cut to extreme close-up of fingers absently picking at the bench paint, 100mm lens.
```

---

## 10. 群戏高潮（Ensemble Climax）

**触发词**：庆祝 / 欢呼 / 胜利 / 团聚 / 集结 / 全员

### 默认方案
| 要素 | 方案 |
|------|------|
| 序列 | 各角色特写快切（每人 1-2s）→ 全景/远景收纳所有人 |
| 运镜 | 特写段固定快切 → 全景段环绕或升降 |
| 角度 | 特写平角 → 全景微仰或鸟瞰 |
| 焦段 | 特写 85mm → 全景 24mm |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 胜利/热血 | 低角度仰拍全景 + 升降上升至鸟瞰，节奏从快切→缓全景 |
| 温馨/团聚 | 中景环绕（Orbit Shot），让每个角色自然入画 |
| 悲壮/集结 | 各角色特写（坚毅表情）→ 慢速拉至远景展示队伍规模 |
| 混乱/众怒 | 手持快切，每角色 < 1s，全景用高角度俯瞰混乱场面 |

### Prompt 片段
```
Quick cuts: close-up of Character A smiling, 85mm lens, 1 second. Close-up of Character B raising fist, 1 second. Close-up of Character C wiping tears, 1 second. Wide shot crane up revealing all characters standing together on a hilltop at sunset, 24mm lens, slow rise from eye-level to slight bird's eye, golden hour light.
```

---

## 11. 转场段落（Transition / Montage）

**触发词**：过渡 / 时间流逝 / 蒙太奇 / 日夜变化 / 成长 / 训练

### 默认方案
| 要素 | 方案 |
|------|------|
| 景别 | 混合——每切一次换一个景别（远→特写→中→远→近…） |
| 运镜 | 短促运镜为主（1-2s 推/拉/横移），制造流动感 |
| 角度 | 多变——每个镜头不同角度增加视觉丰富度 |
| 焦段 | 每镜头变换焦段，避免视觉重复 |
| 节奏 | 快切（每镜 1-3s），总段落 10-30s |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 成长/进步 | 从慢到快逐步加速切换，景别从远到近（接近目标） |
| 时间流逝 | 固定机位相同构图，画面内容变化（日→夜→日），Dissolve 转场 |
| 堕落/衰败 | 逐步加入荷兰角，景别从近到远（远离核心），色调变冷变暗 |
| 欢乐回忆 | 柔焦/过曝效果，暖色，中景为主，节奏轻快 |

### Prompt 片段
```
Montage sequence: Medium shot of hands kneading dough, 50mm lens, 2 seconds. Wide shot of the bakery at dawn, 28mm lens, 1.5 seconds. Close-up of flour dusting a finished loaf, 85mm lens, 1.5 seconds. Medium shot of character wiping forehead with satisfied smile, 50mm lens, 2 seconds. Each shot connected by matching motion cuts.
```

---

## 12. 悬疑 / 恐怖（Suspense / Horror）

**触发词**：恐惧 / 跟踪 / 偷窥 / 危险 / 阴影 / 黑暗 / 诡异

### 默认方案
| 要素 | 方案 |
|------|------|
| 主视角 | POV 镜头（第一人称）+ 客观镜头交替 |
| 景别 | 远景（空间中的未知）↔ 特写（恐惧反应）大跨度切换 |
| 运镜 | 手持轻微晃动（不安感）+ 极缓推（制造等待的恐惧） |
| 角度 | 荷兰角 15-30°（失衡感），低角度（威胁源显得更大） |
| 焦段 | 广角 24mm（空间扭曲恐惧）+ 长焦 200mm（偷窥/被监视感） |

### 情绪变体
| 情绪 | 调整 |
|------|------|
| 跟踪/被监视 | 200mm 长焦固定远景（窥视者视角），树叶/门缝遮挡前景 |
| 密室/幽闭 | 超广角 14mm（空间扭曲）+ 低角度 + 四壁逼近感 |
| Jump Scare | 固定长镜（5s+ 制造安全感）→ 突然甩镜/急推至恐惧源 |
| 心理恐惧 | Dolly Zoom（空间扭曲），角色面部特写+背景缓慢变化 |

### Prompt 片段（跟踪型）
```
Long telephoto shot (200mm) through chain-link fence, voyeuristic perspective watching a woman walk down an empty street at night, compressed perspective flattening the depth. Cut to her POV close-up looking over shoulder, 35mm handheld with slight shake, seeing nothing but shadows. Dutch angle medium shot of the empty street behind her, tilted 20 degrees, streetlight flickering.
```

---

## 使用说明

1. STEP 0 决策树命中场景类型后，来本表查「默认方案」
2. 结合 STEP 0 提取的「情绪基调」，查「情绪变体」调整
3. Prompt 片段可直接嵌入 video-prompt-craft 的时间码提示词
4. 混合场景（如"对话中爆发打斗"）→ 前半段用场景1方案，转折点后切场景2方案
5. 同一场景持续 > 30s → 必须在默认方案基础上加入景别变化，避免视觉疲劳
