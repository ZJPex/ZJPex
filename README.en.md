<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner.svg">
  <img alt="ZJPex — AI / Agent" src="assets/banner.svg">
</picture>

# 周峻锋 / ZJPex

Class of 2027 · AI applications / Agent development

Building deliverable, verifiable AI systems through Agent workflows, tool contracts, state and error handling, task evaluation, and model routing.

[完整作品集 / Portfolio](https://zjpex.github.io/AgentCraft_Portfolio/) · [中文版](README.md)

## Selected projects

### [AlphaPilot](https://github.com/ZJPex/AlphaPilot)

**Position** · An AI workspace for quantitative research and strategy analysis.

**My work** · Personal project: Agent / Skills orchestration, market data services, and artifact validation.

**Challenge** · Connecting data retrieval, generation, and validation for natural-language research.

**Delivery** · Market-data analysis pages with traceable sources, execution records, and evaluations.

### [LLMRouter](https://github.com/ZJPex/LLMRouter)

**Position** · A local LLM routing and management platform.

**My work** · Personal project: Rust gateway, React console, protocol routing, and access governance.

**Challenge** · Unifying Anthropic / OpenAI protocols, streaming tool use, and failover.

**Delivery** · Unified model access, permissions and quotas, request tracing, and health checks.

<!-- contributions:start -->

## Open source

**18 merged PRs · 4 upstream repositories**

Public upstream PRs authored by ZJPex and merged; own repositories excluded.

<!-- featured:start -->
<!-- featured-selection: 6c15ec9ce0e4093a00dcf088ef6cc3cdaa8840a43cfbaeecf6a0eb06291dc08a 97d440ce15541472abe5b05d515dd85e36bc82a01f436baf2685f102cab64954 a5400c06a95b83621e7ef5bf8be8844d5c2225910d9349ba487834ba7917fb32 b08fd6b2ea610afc9e174d061591e8f714cb1c59a18bc16ea9d42026f6be135d e774a51075e3935e654592028cb42749f80f4207d6becbcbe7ad0220964dff23 e499f3cbaff2a6cf9777e04b1e1e43e5581192ce1b65c2e652d023d53348fb2b -->
<!-- project-manual: {"678f85c4492c1e55d2cd2180f5830dbb327a7f5868efb93f6afdbd237ceb0e67": ["Improved the reading experience in streaming chat and version compatibility and failure handling when refreshing the Codex model catalog&#46;", 2], "7ce5cfc208e27666d90652b41f81a3da4dd28e41534a087f53c8f1e7d3a09314": ["Clarified contribution metrics in AI roast prompts to constrain unsupported inferences about activity types and repository ownership&#46;", 1], "b71d171950aadd51241167c0112ee464f2eee734bc1d2457a6714fd5e0ab28ac": ["Improved context recovery&#44; historical data retrieval&#44; and deliverable checks in agent workflows&#44; addressing omissions and edge cases&#46;", 2], "e8cc467aa7be05e0c7903b7211267c2cf66f106a9d1a60e6e42f90aef6e0b7bf": ["Improved model access&#44; tool calls&#44; and error handling across agents to clarify execution boundaries and failure states&#46;", 2]} -->
<!-- project-summary-revisions: {"678f85c4492c1e55d2cd2180f5830dbb327a7f5868efb93f6afdbd237ceb0e67": 1, "7ce5cfc208e27666d90652b41f81a3da4dd28e41534a087f53c8f1e7d3a09314": 1, "b71d171950aadd51241167c0112ee464f2eee734bc1d2457a6714fd5e0ab28ac": 1, "e8cc467aa7be05e0c7903b7211267c2cf66f106a9d1a60e6e42f90aef6e0b7bf": 1} -->
### Selected contributions

| Project / Stars | Merged | Contribution | Representative PRs |
| --- | ---: | --- | --- |
| [deer&#45;flow](https://github.com/bytedance/deer-flow)<br>★ 83570 | 10 | Improved context recovery&#44; historical data retrieval&#44; and deliverable checks in agent workflows&#44; addressing omissions and edge cases&#46; | [#5947](https://github.com/bytedance/deer-flow/pull/5947)<br>[#5570](https://github.com/bytedance/deer-flow/pull/5570) |
| [cindy](https://github.com/makecindy/cindy)<br>★ 2965 | 5 | Improved model access&#44; tool calls&#44; and error handling across agents to clarify execution boundaries and failure states&#46; | [#3043](https://github.com/makecindy/cindy/pull/3043)<br>[#2890](https://github.com/makecindy/cindy/pull/2890) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)<br>★ 40988 | 2 | Improved the reading experience in streaming chat and version compatibility and failure handling when refreshing the Codex model catalog&#46; | [#704](https://github.com/HKUDS/DeepTutor/pull/704) |
| [ghfind](https://github.com/hikariming/ghfind)<br>★ 245 | 1 | Clarified contribution metrics in AI roast prompts to constrain unsupported inferences about activity types and repository ownership&#46; | [#210](https://github.com/hikariming/ghfind/pull/210) |

<!-- featured:end -->

<!-- merged-details:start -->
<details>
<summary>bytedance&#47;deer&#45;flow · 10 merged PRs</summary>

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
<summary>makecindy&#47;cindy · 5 merged PRs</summary>

- [makecindy&#47;cindy#3133](https://github.com/makecindy/cindy/pull/3133) — fix&#40;pi&#41;&#58; report output&#45;limit responses as incomplete · 2026-09-10
- [makecindy&#47;cindy#3043](https://github.com/makecindy/cindy/pull/3043) — fix&#40;claude&#45;code&#41;&#58; preflight subagent model access · 2026-08-19
- [makecindy&#47;cindy#2513](https://github.com/makecindy/cindy/pull/2513) — fix&#40;desktop&#41;&#58; preserve Orca worker provider routing · 2026-08-19
- [makecindy&#47;cindy#2890](https://github.com/makecindy/cindy/pull/2890) — fix&#40;responses&#45;chat&#45;bridge&#41;&#58; compact oversized exec descriptions · 2026-08-18
- [makecindy&#47;cindy#2779](https://github.com/makecindy/cindy/pull/2779) — fix&#40;maker&#45;core&#41;&#58; guard native Claude tool loops · 2026-08-16

</details>

<details>
<summary>HKUDS&#47;DeepTutor · 2 merged PRs</summary>

- [HKUDS&#47;DeepTutor#1317](https://github.com/HKUDS/DeepTutor/pull/1317) — feat&#40;codex&#41;&#58; automatically discover client versions for model catalog refresh · 2026-09-23
- [HKUDS&#47;DeepTutor#704](https://github.com/HKUDS/DeepTutor/pull/704) — fix&#40;web&#41;&#58; respect manual scrolling in partner chat · 2026-07-26

</details>

<details>
<summary>hikariming&#47;ghfind · 1 merged PR</summary>

- [hikariming&#47;ghfind#210](https://github.com/hikariming/ghfind/pull/210) — fix&#40;roast&#41;&#58; 修正年度贡献数的错误归因 · 2026-09-02

</details>

<!-- merged-details:end -->

<!-- contributions:end -->
