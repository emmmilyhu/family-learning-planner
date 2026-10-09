# 家庭学业探索规划 · family-learning-planner

面向小学四至六年级家庭的 AI Skill，帮助家长或老师围绕一个真实问题，形成有依据、可尝试、可复盘的阶段方向。

## 下载

[下载完整技能包（2026-10-09）](https://github.com/emmmilyhu/family-learning-planner/raw/refs/heads/main/family-learning-planner-2026-10-09.zip)

也可以点击仓库中的 ZIP 文件，再点击下载按钮。解压后请保留整个 `family-learning-planner` 文件夹，主文件引用了三个参考文件。

## 使用

将完整文件夹放入支持 Skill 的 AI 工具的技能目录，按该工具的说明启用；或让能读取本地文件的 AI 读取 `family-learning-planner/SKILL.md`，随任务读取对应参考文件。

启动示例：

> 请使用 family-learning-planner 帮我们讨论一个问题。孩子五年级，最近喜欢画漫画，我们想了解是否需要报班。请先了解相关经历、孩子意见和家庭条件，再一起比较选项。

## 适用任务

- 初次家庭学业探索规划。
- 兴趣与学科学习连接。
- 报班、停课与时间安排取舍。
- 小升初资格、政策与节点核验。
- 小行动尝试后的复盘更新。

不用于高中选科、大学或留学申请的具体办理。

## 文件结构

```text
family-learning-planner/
├── SKILL.md
└── references/
    ├── interest-to-learning.md
    ├── school-transition.md
    └── review-and-update.md
```

## 方法与边界

采用基于 GROW 改编的五步对话：目标对齐、孩子现状、家庭条件、候选选项、行动与复盘。孩子通过聊天、作品或试做参与；成人负责必要教育与支持责任。兴趣可以保留为休闲，行业与专业仅按需拓展视野。发展行动与入学事项分别处理，具体政策须核验当年当地官方资料。

AI 输出是可修改草稿，不能推断天赋、人格或职业适配度，也不保证学业或升学结果。不要把私人儿童和家庭记录上传到公开仓库。

版本日期：2026-10-09。文件与引用静态检查及 ZIP 完整性检查通过；标准校验器因环境缺少 PyYAML 未运行成功。尚未完成真实家庭行为验证。
