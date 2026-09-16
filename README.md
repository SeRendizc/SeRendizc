<div align="center">

<img
width="100%"
src="https://capsule-render.vercel.app/api?type=waving&color=0:7AA2F7,50:9D7CD8,100:BB9AF7&height=220&section=header&text=Zhou%20Yuchen%20周宇宸&fontSize=48&fontColor=FFFFFF&fontAlignY=35&desc=AI%20Systems%20%C2%B7%20Agent%20%C2%B7%20AI%20Infra&descAlignY=56&descSize=17&animation=fadeIn"
alt="Yuchen Zhou"
/>

<a href="https://github.com/SeRendizc">
  <img
  width="100%"
  src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1400&color=7AA2F7&center=true&vCenter=true&width=1000&height=55&lines=Building+reliable+systems+around+language+models;From+model+internals+to+inference+protocols+and+agents;Build+the+layer.+Test+the+behavior.+Explain+the+result."
  alt="Typing introduction"
  />
</a>

<br />

[![GitHub](https://img.shields.io/badge/GitHub-SeRendizc-1A1B27?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SeRendizc) [![Email](https://img.shields.io/badge/Email-zhouyuchen%40connect.hku.hk-7AA2F7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zhouyuchen@connect.hku.hk) [![Location](https://img.shields.io/badge/Shenzhen_%C2%B7_Hong_Kong-9D7CD8?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

<br />

### Model Internals　→　Inference Protocols　→　Agent Runtime & Evaluation

<sub>Each layer implemented and measured on its own, then connected into a system that runs.</sub>

</div>

---

## 👋 About

香港大学人工智能硕士在读，本科毕业于武汉大学，获翻译（文学学士）与计算机科学与技术（工学学士）双学位。

近半年聚焦 **Agent** 与 **LLM Inference** 两个方向：工具调用的持久化与崩溃恢复、OpenAI 兼容后端的协议差异、Decoder-only 模型的推理机制。每个实验都附带测试与边界说明，失败路径与限制同样记录在仓库中。

求职方向：**Agent / LLM Infra** 实习，深圳 · 香港。

---

## 🎓 Education

- **香港大学** — 人工智能理学硕士（2026/09 - 2028/07）
- **武汉大学** — 翻译（文学学士） · 计算机科学与技术（工学学士）

---

## 🚀 Selected Projects

**[Agent Runtime Lab](https://github.com/SeRendizc/agent-runtime-lab)** · `Python` · `SQLite` · `Event Sourcing`

基于事件溯源的 Agent 执行框架实验。工具调用前持久化 Intent、调用后写入 Receipt，崩溃恢复时依据工具注册契约在「复用已有结果 / 幂等重试 / 终止并标记结果未知」之间决策；人工审批与提案版本及摘要绑定，提案变更后自动失效。

<br />

**[Agent Eval Lab](https://github.com/SeRendizc/agent-eval-lab)** · `Python` · `OpenAI-compatible`

面向 OpenAI 兼容后端的行为评估工具。以 YAML 用例驱动 Mock、本地服务与托管接口，并将原始响应、解析结果与判定结果分离存储。仓库保留 vLLM 0.26.0 与 SGLang 0.5.16 在同一组用例下的响应对照，其中工具调用 `finish_reason` 的差异已固化为回归样例。

<br />

**[Decoder Inference Lab](https://github.com/SeRendizc/decoder-inference-lab)** · `Python` · `PyTorch`

从零实现的 Decoder-only Transformer。包含 RMSNorm、Causal Attention 与 Pre-Norm 残差块，动态与静态两种 KV Cache 共用同一条前向路径，并提供缓存与全量重算的对比以及 Prefill / Decode 计时脚本。

<br />

**[AI Coding Learning Loop](https://github.com/SeRendizc/ai-coding-learning-loop)** · `Node.js` · `Harness Plugin`

面向 DeepSeek Harness 的 AI 编程协作插件。提供四档人机分工模式，将代码验证结果与学习检查结果分别记录，避免把「测试通过」等同于「已经掌握」。当前为 Alpha 阶段。

<br />

<sub>以上均为学习实验项目，不是生产系统；各自的边界与限制写在对应仓库的 README 中。</sub>

---

## 📊 GitHub

<div align="center">

![Public repos](https://img.shields.io/badge/Public_repos-8-7AA2F7?style=flat-square&logo=github&logoColor=white) ![Since](https://img.shields.io/badge/On_GitHub_since_2022-9D7CD8?style=flat-square&logo=github&logoColor=white) ![Focus](https://img.shields.io/badge/Focus-Agent_%C2%B7_Inference_%C2%B7_Evaluation-BB9AF7?style=flat-square)

</div>

<br />

<div align="center">

### Build the layer · Test the behavior · Explain the result

<sub>
Agent / LLM Infra 方向实习（深圳 · 香港）
</sub>

<br /><br />

<img
width="100%"
src="https://capsule-render.vercel.app/api?type=waving&color=0:7AA2F7,50:9D7CD8,100:BB9AF7&height=115&section=footer"
alt="Footer"
/>

</div>
