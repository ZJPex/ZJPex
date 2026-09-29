<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner.svg">
  <img alt="ZJPex — AI / Agent" src="assets/banner.svg">
</picture>

# 周峻锋 / ZJPex

2027 届 · AI 应用 / Agent 开发

聚焦 Agent 工作流、工具契约、状态与异常处理、任务评测和模型路由，把模型能力推进为可交付、可验证的系统。

[完整作品集 / Portfolio](https://zjpex.github.io/AgentCraft_Portfolio/) · [English](README.en.md)

## 精选项目

### [AlphaPilot](https://github.com/ZJPex/AlphaPilot)

**项目定位** · 智能量化投研与策略分析工作台。

**个人工作** · 个人开发：Agent / Skills 编排、行情服务与产物验证。

**核心挑战** · 串联自然语言投研的取数、生成与验证。

**交付结果** · 生成真实行情分析页，保留来源、运行与评测记录。

### [LLMRouter](https://github.com/ZJPex/LLMRouter)

**项目定位** · 本地大模型路由与管理平台。

**个人工作** · 个人开发：Rust 网关、React 管理端、协议路由与访问治理。

**核心挑战** · 统一 Anthropic / OpenAI 协议，处理流式 Tool Use 与故障切换。

**交付结果** · 统一模型接入、权限配额、请求追踪与健康检查。

<!-- contributions:start -->

## 开源贡献

**13 个已合并 PR · 4 个上游仓库**

仅统计 ZJPex 提交并合并到外部公开仓库的 PR。

<!-- featured:start -->
<!-- featured-selection: 6c15ec9ce0e4093a00dcf088ef6cc3cdaa8840a43cfbaeecf6a0eb06291dc08a 97d440ce15541472abe5b05d515dd85e36bc82a01f436baf2685f102cab64954 a5400c06a95b83621e7ef5bf8be8844d5c2225910d9349ba487834ba7917fb32 b08fd6b2ea610afc9e174d061591e8f714cb1c59a18bc16ea9d42026f6be135d e774a51075e3935e654592028cb42749f80f4207d6becbcbe7ad0220964dff23 e499f3cbaff2a6cf9777e04b1e1e43e5581192ce1b65c2e652d023d53348fb2b -->
<!-- project-manual: {"678f85c4492c1e55d2cd2180f5830dbb327a7f5868efb93f6afdbd237ceb0e67": ["\u4fee\u590d Partner \u6d41\u5f0f\u5bf9\u8bdd\u5f3a\u5236\u6eda\u52a8&#65292;\u4fdd\u7559\u7528\u6237\u67e5\u770b\u5386\u53f2\u6d88\u606f\u7684\u4f4d\u7f6e&#12290;", 2], "7ce5cfc208e27666d90652b41f81a3da4dd28e41534a087f53c8f1e7d3a09314": ["\u7ea6\u675f\u4e2d\u82f1\u6587\u9510\u8bc4\u63d0\u793a\u8bcd&#65292;\u907f\u514d\u628a\u5e74\u5ea6\u8d21\u732e\u603b\u6570\u8bef\u5199\u6210 PR \u6570&#12290;", 1], "b71d171950aadd51241167c0112ee464f2eee734bc1d2457a6714fd5e0ab28ac": ["\u589e\u52a0\u6709\u754c JSON \u8bed\u6cd5\u9a8c\u6536\u6761\u4ef6\u548c\u5386\u53f2\u4e0a\u4f20\u6587\u4ef6\u7684\u7a33\u5b9a\u5206\u9875&#12290;", 2], "e8cc467aa7be05e0c7903b7211267c2cf66f106a9d1a60e6e42f90aef6e0b7bf": ["\u8865\u5145\u5b50 Agent \u6a21\u578b\u6743\u9650\u9884\u68c0&#65292;\u5e76\u7cbe\u7b80\u534f\u8bae\u6865\u63a5\u4e2d\u7684\u8d85\u5927\u5de5\u5177\u63cf\u8ff0&#12290;", 2]} -->
### 代表性贡献

| 项目及 Stars | 已合并数量 | 贡献内容 | 代表性 PR |
| --- | ---: | --- | --- |
| [deer&#45;flow](https://github.com/bytedance/deer-flow)<br>★ 83204 | 5 | 增加有界 JSON 语法验收条件和历史上传文件的稳定分页&#12290; | [#5947](https://github.com/bytedance/deer-flow/pull/5947)<br>[#5570](https://github.com/bytedance/deer-flow/pull/5570) |
| [cindy](https://github.com/makecindy/cindy)<br>★ 2835 | 5 | 补充子 Agent 模型权限预检&#65292;并精简协议桥接中的超大工具描述&#12290; | [#3043](https://github.com/makecindy/cindy/pull/3043)<br>[#2890](https://github.com/makecindy/cindy/pull/2890) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)<br>★ 40489 | 2 | 修复 Partner 流式对话强制滚动&#65292;保留用户查看历史消息的位置&#12290; | [#704](https://github.com/HKUDS/DeepTutor/pull/704) |
| [ghfind](https://github.com/hikariming/ghfind)<br>★ 237 | 1 | 约束中英文锐评提示词&#65292;避免把年度贡献总数误写成 PR 数&#12290; | [#210](https://github.com/hikariming/ghfind/pull/210) |

<!-- featured:end -->

<!-- merged-details:start -->
<details>
<summary>bytedance&#47;deer&#45;flow · 5 个已合并 PR</summary>

- [bytedance&#47;deer&#45;flow#5947](https://github.com/bytedance/deer-flow/pull/5947) — feat&#58; add bounded JSON syntax acceptance criteria · 2026-09-28
- [bytedance&#47;deer&#45;flow#5927](https://github.com/bytedance/deer-flow/pull/5927) — feat&#58; add optional message&#45;role filtering to history&#95;search · 2026-09-27
- [bytedance&#47;deer&#45;flow#5570](https://github.com/bytedance/deer-flow/pull/5570) — feat&#40;tools&#41;&#58; add stable pagination to historical upload discovery · 2026-09-24
- [bytedance&#47;deer&#45;flow#5572](https://github.com/bytedance/deer-flow/pull/5572) — fix&#40;ragflow&#41;&#58; batch validation for large document selections · 2026-09-19
- [bytedance&#47;deer&#45;flow#5544](https://github.com/bytedance/deer-flow/pull/5544) — fix&#40;gateway&#41;&#58; preserve clarification answers on regenerate · 2026-09-19

</details>

<details>
<summary>makecindy&#47;cindy · 5 个已合并 PR</summary>

- [makecindy&#47;cindy#3133](https://github.com/makecindy/cindy/pull/3133) — fix&#40;pi&#41;&#58; report output&#45;limit responses as incomplete · 2026-09-10
- [makecindy&#47;cindy#3043](https://github.com/makecindy/cindy/pull/3043) — fix&#40;claude&#45;code&#41;&#58; preflight subagent model access · 2026-08-19
- [makecindy&#47;cindy#2513](https://github.com/makecindy/cindy/pull/2513) — fix&#40;desktop&#41;&#58; preserve Orca worker provider routing · 2026-08-19
- [makecindy&#47;cindy#2890](https://github.com/makecindy/cindy/pull/2890) — fix&#40;responses&#45;chat&#45;bridge&#41;&#58; compact oversized exec descriptions · 2026-08-18
- [makecindy&#47;cindy#2779](https://github.com/makecindy/cindy/pull/2779) — fix&#40;maker&#45;core&#41;&#58; guard native Claude tool loops · 2026-08-16

</details>

<details>
<summary>HKUDS&#47;DeepTutor · 2 个已合并 PR</summary>

- [HKUDS&#47;DeepTutor#1317](https://github.com/HKUDS/DeepTutor/pull/1317) — feat&#40;codex&#41;&#58; automatically discover client versions for model catalog refresh · 2026-09-23
- [HKUDS&#47;DeepTutor#704](https://github.com/HKUDS/DeepTutor/pull/704) — fix&#40;web&#41;&#58; respect manual scrolling in partner chat · 2026-07-26

</details>

<details>
<summary>hikariming&#47;ghfind · 1 个已合并 PR</summary>

- [hikariming&#47;ghfind#210](https://github.com/hikariming/ghfind/pull/210) — fix&#40;roast&#41;&#58; 修正年度贡献数的错误归因 · 2026-09-02

</details>

<!-- merged-details:end -->

<!-- unmerged:start -->
<details>
<summary>未合并贡献</summary>

以下 PR 未计入已合并统计或代表成果。

- [bytedance&#47;deer&#45;flow#5954](https://github.com/bytedance/deer-flow/pull/5954) — fix&#58; preserve existing task notes during parallel additions · **开放中**
- [bytedance&#47;deer&#45;flow#6008](https://github.com/bytedance/deer-flow/pull/6008) — feat&#58; return hit&#45;centered history search excerpts with source offsets · **开放中**
- [makecindy&#47;cindy#2313](https://github.com/makecindy/cindy/pull/2313) — fix&#40;desktop&#41;&#58; isolate Ghost Skills by profile · **开放中**
- [makecindy&#47;cindy#2782](https://github.com/makecindy/cindy/pull/2782) — fix&#40;desktop&#41;&#58; keep Codex subagent model selection native · **开放中**
- [makecindy&#47;cindy#2936](https://github.com/makecindy/cindy/pull/2936) — fix&#40;orca&#41;&#58; guide safe Code Mode text arguments · **开放中**
- [makecindy&#47;cindy#4232](https://github.com/makecindy/cindy/pull/4232) — feat&#40;project&#45;context&#41;&#58; 支持使用 Codex 维护项目知识 · **开放中**
- [bytedance&#47;deer&#45;flow#5952](https://github.com/bytedance/deer-flow/pull/5952) — fix&#58; preserve existing task notes during parallel additions · **已关闭，未合并**
- [HKUDS&#47;DeepTutor#1251](https://github.com/HKUDS/DeepTutor/pull/1251) — fix&#58; normalize Codex named&#45;function tool choice for Responses · **已关闭，未合并**

</details>
<!-- unmerged:end -->

<!-- contributions:end -->
