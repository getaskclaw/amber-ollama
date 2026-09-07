# amber-ollama

用私有题库 **AMBER** 每周实测 Ollama Cloud 模型，只公开结果，不公开题目。
English: [README.en.md](README.en.md)

## 这是什么

- 每周一期 `results/YYYY-Www.md`：同题、同档、同 harness，对在售模型跑全库。
- 一期固定报告：题集规模与哈希、每案 d2 分与通过/失败、终端终态、成本与时延、环境指纹、按证据纪律写的定性裁决。
- 题目、oracle、transcript、中间产物**永不公开**(见下「发布纪律」)。
- 姐妹仓:[amber-crof](https://github.com/getaskclaw/amber-crof)(CrofAI 周测)。

## 发布纪律(红线)

1. 只发：分数与聚合、成本、速度、定性裁决。
2. 永不发：题目内容、oracle/判分器、transcript、考生工作区、任何能复原题面的中间产物。
3. 每期必钉：模型 ID、effort 档、日期(UTC)、harness 版本、每案内容哈希(bundle_sha)。哈希用于对照 [amber-eval](https://github.com/getaskclaw/amber-eval) 的公开哈希清单，自证题集未变。
4. 案号与题目结构属私有面：公开结果里案例只用稳定别名(A-xxxxxxxx，哈希派生)+ bundle 哈希作句柄；内部案号、变体名、题目描述永不出现。
5. 基调：这是社区周测，不是对厂商的攻击。数据说话，措辞克制。

## 结果索引

| 期 | 内容 | 结论 |
|---|---|---|
| [2026-W36](results/2026-W36.md) | 双模型全库:deepseek-v4-flash:0731 / glm-5.3-flash | glm-5.3-flash 15/21 超前沿锚点（14/21）一案+视觉审查案迄今最高分;同名对决实锤「模型名≠能力」 |

## 免责

与 Ollama 无任何隶属/赞助关系。分数是特定周、特定档位的快照,不构成采购建议。
