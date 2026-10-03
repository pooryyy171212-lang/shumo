# 算法资源整理

> 三份高星资料对照去重：XiaoMaColtAI 算法库 / zhanwen 思维导图 / Lanrzip Python 实现。此处只放**去重后的精华条目**，原始出处见链接。

## 七大类框架（对齐 XiaoMaColtAI 分类）

| 类别 | 常用方法 | Python 实现 | 备注 |
|---|---|---|---|
| 优化 | 线性/整数规划、遗传、模拟退火、粒子群 | [Lanrzip](https://github.com/Lanrzip/Mathematical-Modeling) | scipy + 自写启发式 |
| 预测 | 回归、时间序列、灰色 GM(1,1)、BP/LSTM | 同上 | 注意检验步骤完整性 |
| 评价 | 层次分析、熵权、TOPSIS、模糊综合 | 同上 | 主观+客观组合赋权是加分点 |
| 图论 | 最短路、最小生成树、网络流 | 同上 | networkx 够用 |
| 统计 | 假设检验、方差分析、聚类 | 同上 | — |
| 综合 | 机理建模、元胞自动机、蒙特卡洛 | 同上 | 机理类是拉开差距的地方 |
| 机器学习 | 随机森林、XGBoost、SVM | — | 注意可解释性表述 |

## MATLAB 侧备份

- [HuangCongQing/Algorithms_MathModels](https://github.com/HuangCongQing/Algorithms_MathModels) ⭐2.4k —— 2018 年整理，参考用，非最新实践

## 待办

- [ ] 每类挑 1–2 个"开箱即用"代码模板放进本目录（标注来源与 LICENSE）
- [ ] 2026 国赛 C 题用到的数据处理套路沉淀成笔记
