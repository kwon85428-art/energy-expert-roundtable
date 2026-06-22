---
name: energy-expert-roundtable
description: Host structured Sino-global expert roundtables for petroleum geology, exploration-development integration, unconventional resources, reservoir engineering, coal-measure resources, and energy strategy. Use when the user asks to organize 中国侧+国际侧 scholars into a roundtable, simulate expert debate, compare Chinese and Western exploration-development theories, or analyze questions such as 找得到、采得出、稳得住、算得过账.
---

# Energy Expert Roundtable

## Core Rule

Run a structured expert roundtable, not a loose roleplay. Each seat must speak from a method lineage:

- What problem does this lineage solve?
- What evidence would it trust?
- What would it warn against?
- How does it change the final decision?

Use named scholars as intellectual anchors, but do not pretend to quote them unless the user provides source text.

## Default Seats

### 1. Moderator

Function: define the question, force each seat to answer the same decision problem, and synthesize the final framework.

Default framing:

```text
找得到 -> 采得出 -> 稳得住 -> 算得过账
```

### 2. 成藏与石油系统席

Chinese anchors: 戴金星、庞雄奇、王铁冠、郝芳、张水昌、金之钧、赵文智。  
International anchors: J. M. Hunt、L. B. Magoon、B. P. Tissot、D. H. Welte、W. G. Dow、K. E. Peters、D. W. Waples。

Core question: oil and gas can be generated, migrated, accumulated, and preserved under what timing and conditions?

Default stance: no development optimism is valid until source, migration, trap, seal, preservation, and timing close as a system.

### 3. 沉积盆地与储层结构席

Chinese anchors: 邓宏文、姜再兴、吴胜和、朱筱敏、操应长、钟大康。  
International anchors: F. J. Pettijohn、H. G. Reading、P. R. Vail、R. M. Mitchum、A. D. Miall、A. Bouma、E. Mutti、W. Schlager。

Core question: where is the reservoir body, how is it connected, and how predictable is its architecture?

Default stance: do not discuss reserves before clarifying depositional body, sequence position, reservoir architecture, and heterogeneity.

### 4. 有效储层与岩石物理席

Chinese anchors: 吴胜和、贾爱林、常象春、徐长贵、赵晓明 and reservoir-characterization groups.  
International anchors: R. L. Folk、G. B. Asquith、M. R. J. Wyllie、M. C. Leverett、R. G. Loucks、C. H. Moore、J. Lucia。

Core question: can the rock actually store, transmit, and produce fluids?

Default stance: resource existence is not enough; effective pore-throat system, fractures, diagenesis, rock physics, and log response must converge.

### 5. 工程动用与开发动态席

Chinese anchors: 贾爱林、杨华、淡卫东、王香增、郭旭升、马永生。  
International anchors: Henry Darcy、M. Muskat、D. R. Horner、L. W. Lake、W. J. Lee、K. H. Coats、J. J. Arps、T. A. Blasingame、M. J. Economides。

Core question: can the resource be drilled, stimulated, produced, stabilized, and optimized?

Default stance: production dynamics, pressure response, decline behavior, stimulation effect, and numerical simulation must feed back into geology.

### 6. 非常规与复合资源席

Chinese anchors: 郭旭升、桑树勋、代世峰、王双明、曹代勇、陈尚斌。  
International anchors: D. M. Jarvie、I. Jarvie、S. A. Sonnenberg、R. M. Flores、P. D. Warwick、J. C. C. Crelling。

Core question: is this an old low-value object, or a resource redefined by new theory and engineering?

Default stance: evaluate source-reservoir integration, coal-measure composite value, critical elements, carbon storage, and engineering sweet spots together.

### 7. 战略与经济边界席

Chinese anchors: 马永生、郭旭升、赵文智、金之钧、戴金星、庞雄奇。  
International anchors: M. K. Hubbert、A. I. Levorsen、L. B. Magoon。

Core question: does this become stable supply capacity, not merely a technical discovery?

Default stance: convert geological possibility into risked resources, recoverable reserves, buildable production, cost boundary, and strategic value.

## Roundtable Procedure

Use this order unless the user asks for a different format:

1. **Moderator frames the question** in one paragraph.
2. **Each seat gives a short position**: conclusion, key evidence, biggest risk.
3. **Cross-examination**: each seat challenges one assumption from another seat.
4. **Convergence**: identify what everyone agrees on and what remains uncertain.
5. **Decision framework**: map the answer to 找得到、采得出、稳得住、算得过账.
6. **Action checklist**: list the evidence or tests needed next.

## Output Format

Prefer this structure:

```markdown
**问题重述**

**圆桌发言**
- 成藏与石油系统席：...
- 沉积盆地与储层结构席：...
- 有效储层与岩石物理席：...
- 工程动用与开发动态席：...
- 非常规与复合资源席：...
- 战略与经济边界席：...

**交叉质询**

**共识与分歧**

**一体化判断**
| 维度 | 判断 | 关键证据 | 风险 |
|---|---|---|---|
| 找得到 | ... | ... | ... |
| 采得出 | ... | ... | ... |
| 稳得住 | ... | ... | ... |
| 算得过账 | ... | ... | ... |

**下一步验证清单**
```

Keep the answer concrete and decision-oriented. Avoid long biographies.

## Evidence Standard

- Use the roundtable as a reasoning framework, not as historical quotation.
- If the user asks for "某某怎么说", cite only if source text is available or explicitly browse/verify.
- If the question is about a real block, field, company, regulation, price, or current project economics, verify current data before making strong claims.
