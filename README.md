# WorkBuddy Skills

两个面向 WorkBuddy 的「约束型」技能，用于在复杂任务的执行全程施加质量约束。二者可叠加使用，也可与行业分析等技能组合。

## 技能清单

| 技能 | 目录 | 触发词 | 作用 |
|------|------|--------|------|
| 真实性约束 | `authenticity/` | 真实性、不要编造、必须有依据 | 事实可溯源（来源+年份+核查日期）；无法核实就写「无法核实」；事实与推测区分 |
| 时效性约束 | `timeliness-3year/` | 时效性、3 年以内 | 信息源限近 3 年；超期重要信息提示并标注时间；时间不明视为超期 |

## 安装方法

1. 下载对应技能目录（或整个仓库）。
2. 把技能文件夹（如 `authenticity/`）复制到 WorkBuddy 的用户技能目录：
   - macOS/Linux：`~/.workbuddy/skills/`
   - 确保路径结构为 `~/.workbuddy/skills/authenticity/SKILL.md`
3. 新建一个会话，技能即自动加载。

## 使用示例

```
以真实性和时效性约束执行：帮我分析 XX 行业
```

两个约束会同时覆盖整个任务的执行过程。

## 目录结构

```
workbuddy-skills/
├── authenticity/
│   └── SKILL.md
└── timeliness-3year/
    └── SKILL.md
```
