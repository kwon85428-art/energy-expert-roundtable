# Energy Expert Roundtable

A Reasonix/Codex skill for hosting structured Sino-global expert roundtables on petroleum geology, exploration-development integration, unconventional resources, reservoir engineering, coal-measure resources, CCUS, offshore engineering, pipeline safety, geothermal, and energy strategy.

The skill organizes Chinese and international method lineages into roundtable seats, then evaluates a question through:

```text
找得到 -> 采得出 -> 稳得住 -> 算得过账
```

## What's New in v2

- **187 scholar anchors** across 3 genealogy distillation batches (109 Chinese + 78 international)
- **4 extended seats**: 海洋油气工程、CCUS 与碳管理、管道安全与完整性、地热与新能源
- **Expanded Chinese anchors**: Added 韩大匡、袁士义、李阳、王德民、陈元千、胡文瑞、张群、沈平平、周守为、庞忠和、董绍华 and 30+ more
- **Expanded international anchors**: Added Darcy, Muskat, Leverett, Horner, Arps, Blasingame, Economides, Hubbert, Matheron, Flores, Jarvie, and 30+ more
- **Gated action checklist**: G1 Resource → G2 Appraisal → G3 Pilot → G4 Scale
- **Cross-examination protocol**: each seat challenges one assumption from another seat with evidence-level responses

## What It Does

Structured discussions around questions such as:

- How should we judge whether a deep coalbed methane block is worth appraisal and development?
- Why is exploration-development integration central to Chinese petroleum theory?
- How do Chinese and Western theories complement each other in unconventional resources?
- Which evidence is needed to move from discovery to stable supply capacity?
- Can CCUS turn a marginal gas field into an economically viable project?
- How do pipeline safety decisions change when data is sparse?

## Roundtable Seats

### Default (7 seats)

| Seat | Chinese Anchors | International Anchors |
|---|---|---|
| Moderator | — | — |
| 成藏与石油系统 | 戴金星、庞雄奇、王铁冠、郝芳、张水昌、金之钧、赵文智、张群、冯鹏鑫 | Hunt, Magoon, Tissot, Welte, Dow, Peters, Moldowan, Waples, Barker |
| 沉积盆地与储层结构 | 邓宏文、姜再兴、吴胜和、朱筱敏、操应长、钟大康、付金华、范昌育 | Pettijohn, Reading, Vail, Mitchum, Miall, Bouma, Mutti, Schlager (18 scholars) |
| 有效储层与岩石物理 | 吴胜和、贾爱林、常象春、徐长贵、赵晓明 | Folk, Wyllie, Asquith, Leverett, Loucks, Moore, Lucia, Crelling, Sharma, Hashin |
| 工程动用与开发动态 | 韩大匡、袁士义、李阳、王德民、姜汉桥、程林松、张烈辉、孙贺东、陈元千、潘磊 + 原锚点 | Darcy, Muskat, Horner, Lake, Lee, Coats, Arps, Blasingame, Economides, Stalkup, Pope |
| 非常规与复合资源 | 桑树勋、代世峰、王双明、曹代勇、陈尚斌、张群、朱光辉 + 原锚点 | D.M. Jarvie, I. Jarvie, Sonnenberg, Flores, Warwick, Crelling |
| 战略与经济边界 | 马永生、郭旭升、赵文智、金之钧、胡文瑞、宋新民、刘宏斌、米立军 + 原锚点 | Hubbert, Levorsen, Magoon |

### Extended (4 seats, activated on demand)

| Seat | Chinese Anchors | When to Activate |
|---|---|---|
| 海洋油气工程 | 周守为、米立军、李清平、米洪刚 | Offshore, deepwater, subsea |
| CCUS 与碳管理 | 沈平平、刁玉杰、李茜 | Carbon storage, CO₂-EOR |
| 管道安全与完整性 | 董绍华、帅健、张对红 | Pipeline safety, integrity |
| 地热与新能源 | 庞忠和、高澜 | Geothermal, H₂ storage |

## Scholar Lineage Reference

The seat anchors are derived from three genealogy distillation reports (187 scholars total):

| Batch | Scope | Count | Key Domains |
|---|---|---|---|
| I | Chinese petroleum development & engineering | 46 | 渗流力学、采油工程、试井、开发地质、钻井完井、战略 |
| II | Chinese cross-domain energy | 63 | 海洋油气、煤层气、CCUS、气藏、管道、地热 |
| III | International foundations | 78 | Sedimentology(18), Tectonics(8), Geochem(10), Petrophysics(9), Reservoir Eng(11), Fracturing(8), Unconventional(5), Production(5), Geophysics(3), Petroleum Systems(6) |

## Install

```bash
# Reasonix
cp -R skill/energy-expert-roundtable ~/.reasonix/skills/

# Codex
cp -R skill/energy-expert-roundtable ~/.codex/skills/
```

## Use

```text
用 energy-expert-roundtable 开一个圆桌：中国深部煤层气从找到到规模开发，需要跨越哪些关键门槛？
```

Or in English:

```text
Use energy-expert-roundtable to host a structured roundtable on whether deep coalbed methane in China can pass the gates from discovery to scalable production.
```

## Output

- Question restatement
- Roundtable positions (each seat: conclusion + key evidence + biggest risk)
- Cross-examination (each seat challenges one assumption from another)
- Consensus and disagreement table
- Integrated decision framework (找得到/采得出/稳得住/算得过账)
- Gated action checklist (G1→G4, with priorities)

## Evidence Standard

The skill is a reasoning framework. It uses named scholars as intellectual anchors (method lineage, not fabricated quotation). If the user asks for "某某怎么说", cite only if source text is available or explicitly browse/verify. For real blocks, fields, or current economics, verify current data before making strong claims.
