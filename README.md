# DengZheng Wang · YunYao

天津大学 · AI Agents / Visual Retrieval / Multimodal Systems

围绕智能体应用、工程图纸检索和多模态交互，记录从系统设计到工程实现的实践。

**[浏览项目主页](https://yunyao-9527.github.io/)**

| 项目 | 方向与内容 | 在线入口 |
| --- | --- | --- |
| [强对流预警多智能体系统](https://github.com/YunYao-9527/weather-multi-agent-system) | 以多源气象证据与专业智能体协作，提供可审计的风险研判；支持明确标注的合成观测示例。 | [打开系统](https://yunyao-weather.onrender.com/) |
| [工程图纸智能检索系统](https://github.com/YunYao-9527/cad-drawing-retrieval-system) | 完整模型保留 CLIP 实验与结构重排；公开轻量版执行真实图片密度与边缘检索。 | [打开轻量系统](https://yunyao-cad-visual.onrender.com/) |
| [AgentOps 评测与可观测平台](https://github.com/YunYao-9527/agentops) | 从数据集执行、规则评分到 Trace、Span 和结果持久化，运行可验证的评测闭环。 | [打开系统](https://yunyao-agentops.onrender.com/evaluations) |
| [事务型智能客服 Agent](https://github.com/YunYao-9527/customer-service-agent) | 使用模拟业务库，完成订单查询、退款政策检查、用户确认与失败补偿。 | [打开工作台](https://yunyao-customer-service.onrender.com/) |
| [图文大模型与 AR 沉浸式交互](https://github.com/YunYao-9527/multimodal-ar-exhibition-system) | 原应用源码缺失，公开技术路线、选型与个人贡献记录，不声称当前有可运行 AR 应用。 | [技术档案](https://yunyao-9527.github.io/multimodal-ar-exhibition-system/) |

四个 Python 系统已部署到 Render Free，并通过公网健康与业务流程验证。客服、AgentOps 和气象证据层已接通 DeepSeek 官方模型；密钥仅保存在服务端环境变量，公开演示设置调用次数和输入输出限制。模型费用与免费托管分开计算。免费实例可能休眠，演示数据不保证长期保存；完整 CLIP 不属于当前免费部署。

2026-10-22 自动化回归：气象 45 项、AgentOps 16 项、客服 36 项、CAD 3 项，共 100 项通过。另已完成三个系统的真实 DeepSeek 调用验收，测试结果和实现边界在各仓库中保留。
