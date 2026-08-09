---
title: "京张校准轨：可撤回、可审计的城市AI试验带"
author_github: "lijie19961110-del"
language: "zh"
license: "COMMUNITY-DISPLAY-ONLY"
summary: "以一条公共校准主径串联三处校准庭，把 AI 场景转化为有到期日、人工复核、申诉与撤回路径的城市公共试验。"
tracks: ["civic-agent-governance", "youth-friendly-public-space", "ai-traffic-walkability"]
scenarios: ["ai-traffic-walkability", "public-safety-operations-review", "enterprise-service-copilot"]
iteration: "v1.0"
---

# 京张校准轨 / Jing-Zhang Calibration Line

> **方案状态**：开放共创建议，使用仓库临时粗略边界形成 formal intake 包；不替代正式规划，不构成政府审定、工程可行性、投资或运营承诺。

## 设计依据与资料清单

本方案把资料分成三层：官方公告确认项目、约面积与任务；清权 Agent 任务书确认六项共创任务；临时 polygon 只用于生成、图示和入口自检。`data/source_registry.json` 决定每条资料可以支持什么，处理事实包只作导航。[source:SITE-PACKAGE] [source:OFFICIAL-ANNOUNCEMENT] [source:AGENT-TASKBOOK] [source:SOURCE-REGISTRY] [source:PROCESSED-FACT-PACK] [standard:PROJECT-OFFICIAL-ANNOUNCEMENT] [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK] [depth:existing_conditions_diagnosis]

公开资料仍缺官方总体边界、三处重点区 polygon、控规、道路红线、现状建筑、权属、文保和市政条件；因此建筑与道路只表达空间关系，法定 FAR、高度和工程线位保持 unknown。[source:BOUNDARY-SOURCE] [source:KEY-AREA-SOURCE] [standard:MOHURD-CONTROL-DETAILED-PLANNING] [depth:risk_missing_data] [data:geometry/site_boundary.geojson#SITE-001]

![总体概念与证据边界](assets/figures/site-overview.png)

## 三层范围工作框架

统筹研究范围回答“三区两翼如何形成创新与治理回路”；总体设计范围回答“京张廊道怎样成为连续公共校准基础设施”；重点区域回答“北测、中译、南接怎样落为三种详细设计原型”。公告约 43.6 km²、11.4 km² 与 368.4 ha 是任务事实，临时图形面积不是官方精确面积。[source:OFFICIAL-ANNOUNCEMENT] [standard:PROJECT-OFFICIAL-ANNOUNCEMENT] [depth:three_level_scope_framework] [metric:site_area_sqm] [metric:key_area_count]

官方 polygon 到位后，必须同时替换 `site_boundary` 与 `key_areas`，重新裁切六类用地、建筑候选、绿地、公共空间、道路、分期和场景节点，再生成全部指标、五图、HTML 与 PDF；不能只换一条边界。[data:geometry/key_areas.geojson#PROV-KEY-001] [data:geometry/key_areas.geojson#PROV-KEY-002] [data:geometry/key_areas.geojson#PROV-KEY-003]

![三层范围与空间传导](assets/figures/land-use-structure.png)

## 统筹研究范围产业与未来城市研究

总体名称为“京张校准轨”，英文名 **Jing-Zhang Calibration Line**，简称 **JZ CAL**。标识方向以两条未闭合平行轨和一个可移动刻度点组成：平行轨代表技术与公共利益，缺口代表退出权，刻度点代表每次试验必须留下可追溯记录。字体、图像和企业标识均不嵌入方案，最终视觉需另行清权。[source:AGENT-TASKBOOK] [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK] [depth:overall_spatial_structure]

三大定位被翻译为三个动作：百年京张文化带负责“记忆”，都市 AI 生活体验带负责“体验与申诉”，AI 融合创新带负责“验证与复盘”。五大功能组成闭环：全栈自主创新提出技术命题，创新生态配置要素，AI+场景小规模试验，活力城市接受公众反馈，AI治理决定续期、修订或撤回。中关村科技服务翼负责把验证成果转成服务，小月河场景翼把使用反馈与风险送回三处校准庭。[source:AGENT-TASKBOOK]

六个全球案例仅用于机制比较，不支撑本项目空间控制：

| 案例 | 可转化机制 | 本方案的谨慎转译 |
| --- | --- | --- |
| Kendall Square | 从创新区转向混合、可生活的创新社区 | 研发与日常服务必须通过公共空间相遇 [source:CASE-KENDALL] |
| Singapore one-north | work-live-play-learn 与 living lab | 场景试验必须带使用边界和退出机制 [source:CASE-ONE-NORTH] |
| STATION F | 以项目制而非纯空间招商组织生态 | 校准院按问题批次开放，而不是永久占位 [source:CASE-STATION-F] |
| Maria 01 | 旧建筑适应性利用与生态共聚 | 优先把候选旧空间转为轻介入转译工坊 [source:CASE-MARIA01] |
| Seoul DMC | Media Street 作为技术试验与公共体验界面 | 把京张路径变成可读的测试界面 [source:CASE-SEOUL-DMC] |
| Barcelona Innova Lab / 22@ | 公共利益问题驱动的真实环境试验与一站式治理 | 设公开问题库、统一申请与停止条件 [source:CASE-22BARCELONA] |

## 总体设计范围城市更新与控规深度城市设计

空间结构是“一线、三庭、两翼、多站”：校准主径沿京张遗产廊道形成南北连续慢行骨架；三庭分别承担全栈测试、公共转译和日常协商；东西缝合线连接高校、园区、社区与轨道接驳；12 个场景站点把设备状态、数据边界、人工联系人和到期日公开展示。[data:geometry/roads.geojson#ROAD-001] [data:geometry/constraints.geojson#SCN-01] [standard:MOHURD-URBAN-DESIGN-MEASURES] [depth:overall_spatial_structure]

六类用地分区完整覆盖临时边界，采用自然资源部分类子集：科研 0802、绿地 1401、文化 0803、商业服务 05、社区服务 0702、道路 1207。它们是概念分区，不是已批用地。[standard:MNR-LAND-USE-CLASSIFICATION-GUIDE] [depth:land_use_layout] [data:geometry/land_use.geojson#LU-001] [data:geometry/land_use.geojson#LU-006]

更新方法优先“轻介入、可重排、可撤回”：先开放地面层、连通慢行、补齐公共复核界面，再根据公开评估决定是否进入专业深化。缺法定条件时不提出 FAR、高度和拆除对象；`MOHURD-ARCH-DESIGN-DEPTH-2016` 缺官方文件，只作为资料缺口，不作为已满足标准。[standard:MOHURD-CONTROL-DETAILED-PLANNING] [standard:MOHURD-ARCH-DESIGN-DEPTH-2016] [depth:development_intensity_controls] [depth:height_massing_character]

## 重点区域详细设计

![三处重点区域差异](assets/figures/key-areas.png)

### 众智园AI自主创新加速区｜全栈验证院

定位是“先验证再外溢”。可重排试验棚、低速机器人共行环、端侧算力与治理圆桌围绕清河学习花园布置。每个试验以公开问题、最小数据、性能门槛、人工接管、到期日和失败日志进入；国家级集聚区、交通与水系工程仍待专业团队深化。[data:geometry/key_areas.geojson#PROV-KEY-001] [data:geometry/buildings.geojson#BLDG-003] [depth:three_key_area_detailed_design]

### 北京AI原点社区｜共识转译庭

定位是“把科研成果翻译为可理解的城市服务”。近校转译工坊、模型素养教室、人才生活客厅和公共申诉台构成小尺度网络。五道口与清华东路西口方向只表达步行与接驳关系，不是工程线位；既有建筑的保留、改造或拆除需现状调查与权属同意。[data:geometry/key_areas.geojson#PROV-KEY-002] [data:geometry/buildings.geojson#BLDG-002] [depth:retain_renovate_demolish]

### 大钟寺AI产业聚集区｜城市校准市集

定位是“在日常消费与通勤中协商技术”。四象限步行缝合、算法消费透明说明、设备状态灯和人工申诉台形成城市型公共界面。站点一体化、非机动车组织和商业更新均是概念建议，不代表批准工程或指定企业改造。[data:geometry/key_areas.geojson#PROV-KEY-003] [data:geometry/public_space.geojson#PUBLIC-001] [depth:three_key_area_detailed_design]

## AI 创新生态、人才画像与 AI+ 场景

六类用户画像覆盖“建设者、使用者、维护者和被影响者”：

| 画像 | 主要诉求 | 空间与运营回应 |
| --- | --- | --- |
| 青年研究者 | 可负担试验、跨团队合作 | 全栈验证院 + 项目批次制 |
| 初创团队 | 低门槛验证、合规辅导 | 可重排工坊 + 一站式规则台 |
| 居民与照护者 | 不被迫使用、有人可问 | 退出权休息站 + 人工服务窗 |
| 通勤者与骑行者 | 连续、安全、可绕行 | 校准主径 + 明示设备影响区 |
| 老年人与残障使用者 | 无障碍、低认知负担 | 多模态导视 + 同等线下服务 |
| 运维与一线服务者 | 清晰责任、可停止系统 | 设备台账 + 接管按钮 + 复盘班次 |

场景卡均为建议，数据最小化且要求人工复核：[metric:persona_count] [metric:scenario_node_count] [metric:industrial_test_scenario_count]

| # | 场景 | 空间 | 数据边界 | 人工复核 / 到期 |
| --- | --- | --- | --- | --- |
| 01★ | 开源模型压力测试庭 | 众智园 | 合成与清权测试集 | 专家/公众双评；批次结束即停 |
| 02★ | 机器人低速共行测试 | 众智园 | 设备状态与匿名事件 | 安全员接管；每日窗口到期 |
| 03★ | 端侧隐私推理验证 | AI原点 | 原始数据不离端 | 独立审计；用途变更重审 |
| 04 | 算法消费透明市集 | 大钟寺 | 商品规则与非个人反馈 | 人工客服；30天复盘 |
| 05 | 无障碍路径协助 | 校准主径 | 用户主动输入、即用即删 | 无障碍顾问；季度续期 |
| 06 | 社区照护复核台 | 社区服务界面 | 不采集诊断与身份画像 | 社工终审；个案可撤回 |
| 07 | 热舒适可解释导览 | 蓝绿廊道 | 公共环境传感 | 运维复核；传感器故障停用 |
| 08 | 夜间安全共评议 | 公共空间 | 不做人脸识别，仅事件自报 | 社区议事会；季节性试验 |
| 09 | 青年技能配对教室 | 文化服务带 | 自愿技能标签 | 导师确认；结课删除 |
| 10 | 公共服务申诉助手 | 原点社区 | 问题分类，不自动裁决 | 人工受理；答复后归档 |
| 11 | 遗产口述史检索亭 | 京张廊道 | 清权档案与自愿口述 | 馆员校核；授权可撤回 |
| 12 | 低碳算力调度看板 | 众智园 | 汇总能耗，不公布企业数据 | 运维确认；数据缺失停显 |

★ 为产业测试验证场景。任何场景出现隐私越界、不可解释差别影响、无法人工复核、无申诉入口或到期未复审时停止。[data:geometry/constraints.geojson#SCN-12]

## 用地、建筑规模与拆改留方案

建筑图层只布置八个候选轻量载体，表达“验证—解释—申诉—复盘”空间链，不映射现状房屋。拆改留采用证据门槛：有价值且安全的空间优先保留；能以低扰动满足公共需求的空间候选改造；拆除仅在法定鉴定、权属、社会影响和审批齐备后由专业团队判断；新建优先可拆卸、可转用构件。[data:geometry/buildings.geojson#BLDG-001] [metric:building_footprint_area_sqm] [metric:building_coverage_ratio] [depth:retain_renovate_demolish]

概念建筑基底面积和覆盖比例由 EPSG:4548 复算，置信度低；总建筑面积、FAR、高度均 unknown。图层不能用于投资测算、审批或拆迁结论。[standard:MOHURD-CONTROL-DETAILED-PLANNING] [depth:development_intensity_controls]

## 交通、轨道、市政与公共服务设施

![交通、蓝绿与场景节点](assets/figures/mobility-bluegreen.png)

校准主径承担连续步行、骑行、无障碍和公共解释；三条东西线分别连接大钟寺日常界面、AI 原点知识网络和众智园测试接驳。道路中心线总长是概念关系长度，不是红线或施工线位。[data:geometry/roads.geojson#ROAD-001] [metric:road_centerline_length_m] [depth:traffic_rail_slow_parking]

新型基础设施采用“设备护照”：每个端侧算力、传感或机器人节点公开所有者、用途、数据保存、能耗、人工联系人、到期日和停用状态。市政容量、消防、防洪、供能和管线均待官方专项，不做工程承诺。[depth:municipal_new_infrastructure] [standard:MOHURD-URBAN-DESIGN-MEASURES]

## 蓝绿空间、公共空间与城市风貌

绿地概念面积与比例由四段连续/口袋绿地复算，公共空间由五处校准节点复算；它们用于比较空间意图，不是审定绿地率。[data:geometry/green_space.geojson#GREEN-002] [data:geometry/public_space.geojson#PUBLIC-003] [metric:green_space_area_sqm] [metric:green_ratio] [metric:public_space_area_sqm] [metric:public_space_ratio] [depth:blue_green_public_space]

风貌语言取自铁路“轨、枕、刻度、信号”，但不用仿古造型：细长可逆构件、低饱和金属与木色、可读的设备状态、遮阴和雨洪花园共同塑造公共技术气质。三处 AI 朝圣/荣誉节点为：**贡献刻度广场**记录可核验开源贡献，**失败档案馆**保存撤回与复盘，**共识转译庭**展示公众问题如何改变模型和服务。它们均为可移动、低扰动组件，文保边界到位前不落工程结论。[standard:MOHURD-URBAN-DESIGN-MEASURES] [depth:height_massing_character]

## 更新项目清单、实施政策与分期计划

| 项目包 | 建议动作 | 依赖与停止条件 |
| --- | --- | --- |
| R1 校准主径 | 导视、遮阴、设备护照、无障碍补点 | 道路/文保/消防复核 |
| R2 全栈验证院 | 可重排试验棚与失败日志 | 权属、安评、数据治理 |
| R3 共识转译庭 | 模型素养教室与申诉台 | 运营主体与公共服务确认 |
| R4 城市校准市集 | 算法消费说明与步行缝合 | 站点、交通、商业权属复核 |
| R5 三处荣誉节点 | 贡献、失败、共识三类展示 | 版权、文保与公众评议 |
| R6 场景开放协议 | 统一申请、风险分级、到期复审 | 法务伦理与主管部门确认 |
| R7 公共数据收据 | 个人可查使用、保存与删除 | 数据保护与安全评估 |
| R8 年度校准周 | 公开复盘、开发者维护马拉松 | 活动审批与资金另行确认 |

近期建议先做规则模板、步行审计与可移动组件；中期在公众评议后连成三庭网络；远期只在 official polygons 与专项资料到位后重算并由专业团队深化。[data:geometry/phasing.geojson#PHASE-001] [metric:phase_area_1_sqm] [metric:phase_area_2_sqm] [metric:phase_area_3_sqm] [depth:renewal_project_list] [depth:phasing_implementation]

长期运营采用“春季问题征集—夏季小规模试验—秋季校准周—冬季归档与续期”的年度循环；开发者社区同时维护文档、无障碍和故障响应；国际传播只展示可复现证据，不把投稿说成入选或落地。所有活动、招商、政策和资金均是概念建议。[source:AGENT-TASKBOOK]

## 指标体系、面积复算与合规矩阵

![指标与证据链](assets/figures/metrics-evidence.png)

所有已知指标统一由 GeoJSON 或正文可读表复算：[metric:site_area_sqm] [metric:building_footprint_area_sqm] [metric:building_coverage_ratio] [metric:green_space_area_sqm] [metric:green_ratio] [metric:public_space_area_sqm] [metric:public_space_ratio] [metric:road_centerline_length_m] [metric:key_area_count] [metric:scenario_node_count] [metric:industrial_test_scenario_count] [metric:persona_count] [metric:phase_area_1_sqm] [metric:phase_area_2_sqm] [metric:phase_area_3_sqm]。面积采用 EPSG:4548，交换坐标为 EPSG:4326；临时边界导致空间指标置信度为 medium/low。法定 FAR、高度、道路面积和总建筑面积保持 unknown，不进入图面承诺。[depth:metrics_recalculation]

`compliance_matrix.json` 覆盖公告 1.3、1.4、1.5 与 agent.1—agent.6；`standard_matrix.json` 区分已响应标准与缺失官方文件；`design_depth_matrix.json` 把每个深度项指向正文、图层、指标、图纸和自检。机器 PASS 只代表可进入内容审稿，不代表方案优秀、获批或实施。

## 风险、版权与合规说明

主要风险包括：临时边界误读、概念建筑被误当拆改留结论、AI 场景滑向监控、无障碍替代服务不足、遗产控制未知、运营主体和资金未确认。控制措施是醒目标注 provisional、保持法定指标 unknown、默认到期、人工复核、申诉/退出、失败归档与外部专业审查。[depth:risk_missing_data] [data:geometry/constraints.geojson#CONSTRAINT-001]

边界风险通过 `CONSTRAINT-001` 虚线提示、`A-BOUNDARY-001` 假设和全部图件页脚共同披露；官方多边形到位后，若任何设计要素落在新边界外，整包停止沿用并重算。建筑与道路风险通过低置信度指标、候选构件措辞和 unknown 法定控制隔离：不得把概念基底当作拆迁或建设规模，也不得把中心线当作道路红线。AI 场景风险通过设备护照、最小数据、人工接管、申诉渠道、到期复审和失败档案形成可操作的停止链；没有线下替代服务时不得上线。遗产、消防、无障碍、市政、数据保护和活动安全分别需要相应专业团队复核，任何复核未完成只允许讨论，不进入工程或运营承诺。

公开包不含个人数据、企业内部数据、秘密地图或未清权资料；全球案例仅比较机制，不复制图像，不推导本项目空间控制。对外传播必须区分“投稿、审稿、入选、落地”，不得暗示官方背书。上述边界直接影响图层解释、指标置信度、图纸注释和自检状态，而不是只放在免责声明中。

图件由本方案 GeoJSON、metrics 和矩阵程序化生成，字体使用本机系统字形，不含外部地图瓦片、人物、企业商标或未清权图片。全球案例只做文字机制比较；版权与生成说明见 `report/copyright_statement.md`。

## 参考资料

- 项目公告与本地标准快照 [source:OFFICIAL-ANNOUNCEMENT] [standard:PROJECT-OFFICIAL-ANNOUNCEMENT]
- 面向智能体任务书 [source:AGENT-TASKBOOK] [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]
- 城市设计管理办法 [standard:MOHURD-URBAN-DESIGN-MEASURES]
- 控制性详细规划编制审批办法 [standard:MOHURD-CONTROL-DETAILED-PLANNING]
- 国土空间用地用海分类指南 [standard:MNR-LAND-USE-CLASSIFICATION-GUIDE]
- 建筑工程设计文件编制深度规定（缺官方文件，作为资料缺口） [standard:MOHURD-ARCH-DESIGN-DEPTH-2016]
