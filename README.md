# DIKWP-SINOTRACE²

中国人工智能意图兑现、结构转轨、风险触发与国际差分预测系统。

## 目标

把政策讲话、国家规划、模型发布、智能体部署、算力能源、权利风险和国际竞争编译成可结算的12个月预测合同。系统不把“机器思考”“AGI”“普惠”等词设为固定定义，而追踪其背后的可观察关系。

## 运行

```bash
PYTHONPATH=src python -m dikwp_sinotrace2.cli --trials 20000 --seed 7192026
PYTHONPATH=src pytest -q
```

## 输出

- `outputs/forecast_contracts.csv`：机器可读预测合同
- `outputs/policy_speech_trace.json`：讲话到行动的非定义关系编译
- `outputs/international_differential.json`：中国、美国、欧盟差分向量
- `outputs/scenario_summary.json`：结构情景压力测试
- `outputs/dashboard.html`：离线仪表盘

## 边界

概率为2026-07-19的种子快照，不是已经积累多年结算记录的校准结果。系统不自动执行政策，不提供投资建议，也不把模型表现等同于意识或主体资格。
