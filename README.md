# roundtable-skill

圆桌派 —— 让你蒸馏的名人 Skill 坐在一起讨论你的问题。

## 用法

```
圆桌派：[你的问题]，嘉宾：[嘉宾1]、[嘉宾2]、[嘉宾3]
```

## 示例

```bash
# 投资决策
圆桌派：茅台 1800 要不要买入？嘉宾：芒格、塔勒布、散户乙

# 创业方向
快速圆桌：要不要做 AI 独立开发？嘉宾：Paul Graham、Naval、张一鸣

# 辩论模式
辩论：比特币是黄金还是泡沫？正方：Saylor，反方：芒格
```

## 原理

每个嘉宾 = 一个独立 subagent，加载对应的人物 perspective skill，
从各自的思维框架出发独立分析你的问题，最后由主持人汇总综合建议。

## 依赖

- 各 perspective skill（munger-skill, taleb-skill 等）
- delegate_task（并行 subagent）
