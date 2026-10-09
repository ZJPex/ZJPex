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

**18 个已合并 PR · 4 个上游仓库**

仅统计 ZJPex 提交并合并到外部公开仓库的 PR。

<!-- featured:start -->
<!-- featured-selection: 6c15ec9ce0e4093a00dcf088ef6cc3cdaa8840a43cfbaeecf6a0eb06291dc08a 97d440ce15541472abe5b05d515dd85e36bc82a01f436baf2685f102cab64954 a5400c06a95b83621e7ef5bf8be8844d5c2225910d9349ba487834ba7917fb32 b08fd6b2ea610afc9e174d061591e8f714cb1c59a18bc16ea9d42026f6be135d e774a51075e3935e654592028cb42749f80f4207d6becbcbe7ad0220964dff23 e499f3cbaff2a6cf9777e04b1e1e43e5581192ce1b65c2e652d023d53348fb2b -->
<!-- project-manual: {"678f85c4492c1e55d2cd2180f5830dbb327a7f5868efb93f6afdbd237ceb0e67": ["\u6539\u5584\u6d41\u5f0f\u5bf9\u8bdd\u7684\u9605\u8bfb\u4f53\u9a8c&#65292;\u5e76\u589e\u5f3a Codex \u6a21\u578b\u76ee\u5f55\u5237\u65b0\u65f6\u7684\u7248\u672c\u517c\u5bb9\u4e0e\u5931\u8d25\u5904\u7406&#12290;", 2], "7ce5cfc208e27666d90652b41f81a3da4dd28e41534a087f53c8f1e7d3a09314": ["\u6f84\u6e05 AI \u9510\u8bc4\u7684\u8d21\u732e\u7edf\u8ba1\u53e3\u5f84&#65292;\u7ea6\u675f\u5bf9\u8d21\u732e\u7c7b\u578b\u548c\u4ed3\u5e93\u5f52\u5c5e\u7684\u65e0\u4f9d\u636e\u63a8\u65ad&#12290;", 1], "b71d171950aadd51241167c0112ee464f2eee734bc1d2457a6714fd5e0ab28ac": ["\u5b8c\u5584 Agent \u5de5\u4f5c\u6d41\u4e2d\u7684\u4e0a\u4e0b\u6587\u6062\u590d&#12289;\u5386\u53f2\u8d44\u6599\u68c0\u7d22\u4e0e\u4ea7\u7269\u9a8c\u6536&#65292;\u5904\u7406\u9057\u6f0f\u548c\u8fb9\u754c\u60c5\u51b5&#12290;", 2], "e8cc467aa7be05e0c7903b7211267c2cf66f106a9d1a60e6e42f90aef6e0b7bf": ["\u6539\u8fdb\u591a Agent \u7684\u6a21\u578b\u63a5\u5165&#12289;\u5de5\u5177\u8c03\u7528\u4e0e\u5f02\u5e38\u5904\u7406&#65292;\u8ba9\u6267\u884c\u8fb9\u754c\u548c\u5931\u8d25\u72b6\u6001\u66f4\u6e05\u6670&#12290;", 2]} -->
<!-- project-summary-revisions: {"678f85c4492c1e55d2cd2180f5830dbb327a7f5868efb93f6afdbd237ceb0e67": 1, "7ce5cfc208e27666d90652b41f81a3da4dd28e41534a087f53c8f1e7d3a09314": 1, "b71d171950aadd51241167c0112ee464f2eee734bc1d2457a6714fd5e0ab28ac": 1, "e8cc467aa7be05e0c7903b7211267c2cf66f106a9d1a60e6e42f90aef6e0b7bf": 1} -->
### 代表性贡献

| 项目及 Stars | 已合并数量 | 贡献内容 | 代表性 PR |
| --- | ---: | --- | --- |
| [deer&#45;flow](https://github.com/bytedance/deer-flow)<br>★ 83538 | 10 | 完善 Agent 工作流中的上下文恢复&#12289;历史资料检索与产物验收&#65292;处理遗漏和边界情况&#12290; | [#5947](https://github.com/bytedance/deer-flow/pull/5947)<br>[#5570](https://github.com/bytedance/deer-flow/pull/5570) |
| [cindy](https://github.com/makecindy/cindy)<br>★ 2961 | 5 | 改进多 Agent 的模型接入&#12289;工具调用与异常处理&#65292;让执行边界和失败状态更清晰&#12290; | [#3043](https://github.com/makecindy/cindy/pull/3043)<br>[#2890](https://github.com/makecindy/cindy/pull/2890) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)<br>★ 40953 | 2 | 改善流式对话的阅读体验&#65292;并增强 Codex 模型目录刷新时的版本兼容与失败处理&#12290; | [#704](https://github.com/HKUDS/DeepTutor/pull/704) |
| [ghfind](https://github.com/hikariming/ghfind)<br>★ 244 | 1 | 澄清 AI 锐评的贡献统计口径&#65292;约束对贡献类型和仓库归属的无依据推断&#12290; | [#210](https://github.com/hikariming/ghfind/pull/210) |

<!-- featured:end -->

<!-- merged-details:start -->
<details>
<summary>bytedance&#47;deer&#45;flow · 10 个已合并 PR</summary>

- [bytedance&#47;deer&#45;flow#6492](https://github.com/bytedance/deer-flow/pull/6492) — fix&#40;subagents&#41;&#58; scope Go zero&#45;test summaries to individual packages · 2026-10-08
- [bytedance&#47;deer&#45;flow#6443](https://github.com/bytedance/deer-flow/pull/6443) — feat&#40;memory&#41;&#58; add scoped fact lookup by ID · 2026-10-08
- [bytedance&#47;deer&#45;flow#6422](https://github.com/bytedance/deer-flow/pull/6422) — fix&#40;agents&#41;&#58; bound structured tool&#45;output previews · 2026-10-07
- [bytedance&#47;deer&#45;flow#6369](https://github.com/bytedance/deer-flow/pull/6369) — fix&#40;tool&#45;output&#41;&#58; count logical CSV&#47;TSV records in table synopses · 2026-10-06
- [bytedance&#47;deer&#45;flow#5954](https://github.com/bytedance/deer-flow/pull/5954) — fix&#58; preserve existing task notes during parallel additions · 2026-09-30
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

<!-- contributions:end -->
