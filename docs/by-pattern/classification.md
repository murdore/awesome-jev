# Classification

<sub>[awesome-jev](../../README.md) · [中文](classification.zh-CN.md)</sub>

_Put an item into a taxonomy, including deep hierarchies walked with probabilities._

Every catalogued example of this decision — 119 of them, official first, then rows with code, then by stars. The same rows, with caveats, are in [the index](../../README.md#classification); [the site](https://kydlikebtc.github.io/awesome-jev/?p=classification&lang=en) can filter them further by language, primitive and kind.

- **[Cookbook: Classification using confidence](https://docs.typesafe.ai/cookbooks/classification_using_confidence)** ⭐ — Classifies annual reports into 75 industry groups, then reads the answer's own confidence to decide whether to report that group or the broader division above it.
  <sub>`Official docs` · `Py` · `choice`</sub>

- **[Cookbook: Hierarchical classification](https://docs.typesafe.ai/cookbooks/hierarchical_classification)** ⭐ — Walks deep patent, retail, biomedical and source-code taxonomies with a parallel beam search over Choice probabilities.
  <sub>`Official docs` · `Py` · `choice`</sub>

- **[Cookbook: Knowledge graph entity alignment](https://docs.typesafe.ai/cookbooks/entity_alignment)** ⭐ — Decides which of 450 candidate pairs from two product catalogues describe the same thing, with one Score whose three levels are the three available actions.
  <sub>`Official docs` · `Py` · `score`</sub>

- **[Cookbook: Structure recovery](https://docs.typesafe.ai/cookbooks/autoformat)** ⭐ — Reconstructs Markdown from plain text that lost its formatting, in two requests: one restitches hard-wrapped lines, one classifies every block.
  <sub>`Official docs` · `Py`</sub>

- **[worldmonitor: news threat classification](https://github.com/koala73/worldmonitor)** — Two Choice questions over threat level and category, held in shadow mode after a blind evaluation found Jev merely tied the incumbent model.
  <sub>`Benchmark` · ★87,614 · `TS` · `choice` · ⚠ `shadow mode`</sub>

- **[json-render](https://github.com/vercel-labs/json-render)** — Vercel Labs' generative UI framework. In its Jev experiment the model does not write JSON token by token — it only picks components, props and layout.
  <sub>`Project` · ★18,436 · Vercel Labs · `TS` · `choice`</sub>

- **[Inbox Zero: seven email decisions](https://github.com/elie222/inbox-zero)** — Seven distinct email decisions, each with its own separately chosen threshold, falling back to the normal LLM on any error.
  <sub>`Project` · ★12,373 · `TS` · `choice` · `noul`</sub>

- **[tax-doc-classifier](https://github.com/kyotofin/tax-doc-classifier)** — Tax document page classifier built on Jev decisions. 100% strict accuracy across 261 IRS forms, ~$0.001 per page.
  <sub>`Project` · ★484 · kyotofin · `TS`</sub>

- **[docjev](https://github.com/jerryjliu/docjev)** — A very fast document classifier/splitter using Jev
  <sub>`Project` · ★482 · jerryjliu · `Py`</sub>

- **[jev-mcp](https://github.com/jkudish/jev-mcp)** — A ready-made judgement toolbox for agents: fact verification, content screening, semantic ranking, classification and extraction as separate tools.
  <sub>`Plugin` · ★463 · `JS` · `choice` · `score` · `noul`</sub>

- **[classifier-dev](https://github.com/mrmps/classifier-dev)** — Zero-shot text classification over plain HTTP — no API key, no account. One Cloudflare Worker, a CLI, and an MCP server. https://classifier.dev
  <sub>`Plugin` · ★423 · mrmps · `TS`</sub>

- **[pg-jev](https://github.com/realZachi/pg-jev)** — A real PostgreSQL extension exposing the primitives as SQL functions, so a semantic decision can appear in a WHERE clause over any row type.
  <sub>`Project` · ★381 · `Py` · `sh` · `choice` · `score` · `noul`</sub>

- **[unclutter](https://github.com/kitze/unclutter)** — A browser extension that removes page clutter, with reusable template rules.
  <sub>`Project` · ★341 · kitze · `TS`</sub>

- **[perch: semantic code linting](https://github.com/lakeday-org/perch)** — Tree-sitter finds and ranks methods, then user-authored YAML rules compile into nouls, with severity read as the rubric's expected value rather than the top band.
  <sub>`Project` · ★316 · `JS` · `choice` · `score` · `noul`</sub>

- **[Probing Jev's behaviour with repeated API calls](https://github.com/ahastudio/til)** — Independent Korean-language notes reporting that reversing the order of options shifted a probability enough to flip a 0.9 threshold.
  <sub>`Benchmark` · ★191 · `Py` · ⚠ `no licence` `unverified claims`</sub>

- **[Jev-X-Sentiment-Analysis](https://github.com/brainstormity/Jev-X-Sentiment-Analysis)** — An on-demand crypto market terminal: pick a coin and a tweet sample, and Jev turns market data, funding rates and social sentiment into a Buy, Sell, Hold or Take Profit decision card. It never places trades.
  <sub>`Project` · ★174 · brainstormity · `Py`</sub>

- **[332_lab-jev-chat](https://github.com/Liyucheng1997/332_lab-jev-chat)** — A Windows WeChat assistant: Jev judges the intent of each incoming message and DeepSeek suggests replies.
  <sub>`Project` · ★161 · liyucheng1997 · `Kt`</sub>

- **[taskuary](https://github.com/ldbumble/taskuary)** — Automate your job: local-first AI task hub. Email, Teams, Slack & reports -> one timeline -> AI triage -> your coding agents (Claude Code, Codex, Gemini) do the work, you approve.
  <sub>`Plugin` · ★129 · ldbumble · `Py`</sub>

- **[Prism](https://github.com/irfndi/prism-liquidity-agent)** — Does not place orders. It judges market conditions such as toxic flow and mean reversion, and hands the assessment to the existing strategy.
  <sub>`Project` · ★119 · `TS` · `choice` · `score`</sub>

- **[jev-arena](https://github.com/NanmiCoder/jev-arena)** — An introduction to Jev with hands-on tests: Choice, Score and Noul turn natural language into typed judgements for classification, scoring and routing, compared with DeepSeek on comment labelling, speed and results, with CSV import, replay and offline reports.
  <sub>`Benchmark` · ★113 · nanmicoder · `JS`</sub>

- **[youtube-sponsor-detection](https://github.com/trungdq88/youtube-sponsor-detection)** — Detect youtube sponsor segment with live audio and transcript powered by Jev
  <sub>`Project` · ★109 · trungdq88 · `JS` · ⚠ `no licence`</sub>

- **[Blink](https://github.com/ellipsis-dev/blink)** — Uses Jev as a codebase navigator: at each directory level it decides which files are most relevant to the question, then descends.
  <sub>`Project` · ★93 · `TS` · `choice` · ⚠ `no licence`</sub>

- **[pg_typesafe](https://github.com/giuliosmall/pg_typesafe)** — Pre-alpha PostgreSQL extension for TypeSafe AI (Jev) categorical classification
  <sub>`Plugin` · ★88 · giuliosmall · `C`</sub>

- **[typesafe-adblock](https://github.com/realZachi/typesafe-adblock)** — A Chrome extension that asks whether a DOM element is an advert.
  <sub>`Project` · ★88 · realzachi · `JS`</sub>

- **[SemDecide](https://github.com/sharziki/semdecide)** — Jev as a command-line tool: classify, score and filter straight from a shell, for crawlers, CI and data pipelines.
  <sub>`Plugin` · ★74 · `Py` · `sh` · `choice` · `score` · `noul`</sub>

- **[ha-jev](https://github.com/AboveColin/HA-Jev)** — A Home Assistant integration: typed answers as sensors, with actions for automations.
  <sub>`Integration` · ★69 · abovecolin · `Py`</sub>

- **[JevIntent](https://github.com/Nisaka520/JevIntent)** — A WeChat plugin (FkWeChat): long-press a message to analyse its intent, emotion and a suggested reply stance, shown only as a local hint the sender never sees.
  <sub>`Project` · ★64 · nisaka520 · `Java`</sub>

- **[jgrep (npm: jevgrep)](https://github.com/kyu1204/jgrep)** — grep for what code does: one Noul per code chunk, diff hunk or CSV row, printed as file:line hits with probabilities. --diff gates a PR in CI on a rule written in English (exit 0 match / 1 clean / 2 error); --tests lists the test files a diff can affect.
  <sub>`Project` · ★58 · kyu1204 · `TS` · `noul` · `choice` · `score` · ⚠ `unverified claims`</sub>

- **[jev-sift](https://github.com/kbhuw/jev-sift)** — Classify first. Read selectively. A portable agent plugin and MCP tool for batch text classification.
  <sub>`Plugin` · ★48 · kbhuw · `JS` · ⚠ `no licence`</sub>

- **[jev-poly-crypto-demo](https://github.com/frankda/jev-poly-crypto-demo)** — A research tool for Polymarket's five-minute BTC Up/Down markets: live market data becomes Jev class scores, independent logic decides, and a dashboard shows it. Paper trading only; it never connects a wallet.
  <sub>`Project` · ★39 · frankda · `TS` · ⚠ `no licence`</sub>

- **[jev-guard](https://github.com/klauswg/jev-guard)** — Real-time risk triage gateway for exchange deposits and withdrawals — Jev (TypeSafe System One) handles triage only; adjudication stays in deterministic code.
  <sub>`Project` · ★37 · klauswg · `Java`</sub>

- **[commit-miner](https://github.com/devanshbatham/commit-miner)** — Classify Git commit diffs and messages with Jev. Bug fixes, security fixes/CWEs, and change types.
  <sub>`Project` · ★36 · devanshbatham · `Rs` · ⚠ `no licence`</sub>

- **[jev-calibrate](https://github.com/smkrv/jev-calibrate)** — Calibrate Jev questions against your own labels: tune criteria on labelled examples, confirm on a held-out set, get a verdict per question. Unofficial.
  <sub>`Project` · ★32 · smkrv · `TS`</sub>

- **[jev-code](https://github.com/FrancoisChastel/jev-code)** — Jev, TypeSafe's System One classifier, as a tool inside Claude Code, Codex, Pi, and OpenCode: typed classify, check, score, rank, and ask, plus one-command setup.
  <sub>`Plugin` · ★32 · francoischastel · `TS`</sub>

- **[sharp](https://github.com/tshmieldev/sharp)** — Filter your X.com feed with Jev or any LLM
  <sub>`Project` · ★31 · tshmieldev · `TS`</sub>

- **[jev-mcp](https://github.com/blakestone-x/jev-mcp)** — An MCP server exposing classify, score, check, match and screen to any agent.
  <sub>`Plugin` · ★26 · blakestone-x · `Py`</sub>

- **[jev-column-race](https://github.com/goodrahstar/jev-column-race)** — Jev vs Gemini 3.8 Flash: labelling 1,000 app reviews, 4.1× faster and 7× cheaper
  <sub>`Project` · ★24 · goodrahstar · `JS`</sub>

- **[dsh-jev-interceptor](https://github.com/AskTheWay/dsh-jev-interceptor)** — ⚡ Millisecond System-1 judgement for every tool call in DeepSeek Harness — Jev-powered risk classification & evidence-gated auto-approval. Fail-closed by construction. dsh 生态第一个 System-1 决策插件
  <sub>`Plugin` · ★22 · asktheway · `TS`</sub>

- **[evoke](https://github.com/evoke-build/evoke)** — Software, by reflex. A sentence becomes a call of a small program, chosen by Jev, TypeSafe AI's classifier, and run only when it is sure enough. Reflexes are recipes anyone can write, share and improve. A CLI you talk to, a package manager for reflexes from git, and a TypeScript SDK.
  <sub>`Project` · ★22 · evoke-build · `Rs`</sub>

- **[jev-gmail-ai-spam-filter-and-labeling](https://github.com/ilyamk/jev-gmail-ai-spam-filter-and-labeling)** — Self-hosted AI email classifier for Gmail powered by Jev. Create custom labels, organize your inbox, and filter spam with confidence and cost controls.
  <sub>`Project` · ★22 · ilyamk · `JS`</sub>

- **[x-scanner](https://github.com/oso95/x-scanner)** — Chrome extension that labels every post you scroll past on X with typed Jev judgments and a live cost counter
  <sub>`Plugin` · ★22 · oso95 · `TS`</sub>

- **[jevframe](https://github.com/ktaletsk/jevframe)** — Semantic AI for pandas and Polars: classify text, analyze sentiment, and score DataFrame rows with natural-language questions and full probabilities using TypeSafe Jev.
  <sub>`Project` · ★21 · ktaletsk · `Py`</sub>

- **[jev-mail-classifier](https://github.com/parth-kp/jev-mail-classifier)** — Classify your inbox with Jev (TypeSafe's System One model) — tag, move, flag, and notify, all config-driven.
  <sub>`Project` · ★19 · parth-kp · `Py`</sub>

- **[wechat-jev-assistant](https://github.com/yushen100/wechat-jev-assistant)** — A Windows WeChat conversation assistant: reads chats locally, redacts them, has TypeSafe Jev judge them, and keeps an encrypted history.
  <sub>`Project` · ★19 · yushen100 · `Py` · ⚠ `no licence`</sub>

- **[jevlogs](https://github.com/reachjalil/jevlogs)** — Open-source Jev log triage for OpenTelemetry. Score the signal before expensive LLM analysis.
  <sub>`Project` · ★17 · reachjalil · `JS`</sub>

- **[lkclean](https://github.com/stefw/lkclean)** — Chrome extension that cleans up your LinkedIn feed: hides engagement bait, self-promo and off-topic posts using Jev, TypeSafe AI's typed classification model — and explains every decision.
  <sub>`Plugin` · ★16 · stefw · `TS`</sub>

- **[JevBystander](https://github.com/Nisaka520/JevBystander)** — An Android accessibility reader for WeChat: it only reads the screen and pops three toasts — intent, emotion, urgency, a suggestion — and never writes or sends a reply. No third-party dependencies; an 861 KB APK.
  <sub>`Project` · ★15 · nisaka520 · `Kt`</sub>

- **[jev-agent-browser](https://github.com/forvela/jev-agent-browser)** — Fast, bounded browser agents powered by Jev and agent-browser — typed actions, research, classification, and safe orchestration.
  <sub>`Project` · ★14 · forvela · `JS`</sub>

- **[local-jev](https://github.com/amithgc/local-jev)** — A local, offline System One server compatible with TypeSafe's Jev API. It answers typed yes/no, category and score questions with small open models.
  <sub>`Project` · ★13 · amithgc · `Py`</sub>

- **[sift](https://github.com/bohutang/sift)** — Chrome extension that labels every post on X (Substance · Humor · Chit-chat · Promo · Junk · AI-written) with TypeSafe Jev, and hides the ones you don't want.
  <sub>`Plugin` · ★13 · bohutang · `JS`</sub>

- **[jev-ultralightspeed](https://github.com/collapseindex/jev-ultralightspeed)** — Answers one question over a pile of text — tickets, reviews, logs — by packing many items into each request, and reports 32x the throughput of one request per item at 41% lower cost.
  <sub>`Project` · ★12 · collapseindex · `Py` · ⚠ `unverified claims`</sub>

- **[augustus](https://github.com/24601/Augustus)** — Agent skill for the decision-model class (classifiers, encoders/decoders, specialized AR heads, System One). TypeSafe Jev is the dominant exemplar. Composition algebra, question design, validation gates. MIT.
  <sub>`Plugin` · ★11 · 24601 · `Py`</sub>

- **[jev-tree](https://github.com/reachjalil/jev-tree)** — Recursive Jev choice over a taxonomy. Select from more than 255 options without breaking TypeSafe Jev's choice cap.
  <sub>`Project` · ★10 · reachjalil · `TS`</sub>

- **[twitter-jev-guard](https://github.com/qs-lll/twitter-jev-guard)** — Uses TypeSafe Jev to spot low-quality, spam and advertising posts on the X/Twitter timeline and stamps a conspicuous translucent watermark over their text.
  <sub>`Plugin` · ★9 · qs-lll · `JS` · ⚠ `no licence`</sub>

- **[jev-dsl](https://github.com/inanna-malick/jev-dsl)** — Agent-first Haskell DSL for TypeSafe's Jev judgment model: typed packets, inferred types, answers under the same labels
  <sub>`Project` · ★8 · inanna-malick · `Hs`</sub>

- **[one-system](https://github.com/rawwerks/one-system)** — Use local and hosted classifiers aka decision models aka Jev-like models, all through a single TypeSafe API
  <sub>`Jev-like alternative` · ★8 · rawwerks · `TS` · ⚠ `not Jev itself`</sub>

- **[duckdb-jev](https://github.com/prasanthj/duckdb-jev)** — High-throughput, robust native DuckDB extension for batched and streaming TypeSafe/Jev classification, scoring, and semantic predicates from SQL.
  <sub>`Plugin` · ★7 · prasanthj · `C++`</sub>

- **[jlink](https://github.com/keltokhy/jlink)** — Record linkage for economists: write the match rule in plain English, get a probability per pair, audit it, cite it. Python, CLI, Stata and R.
  <sub>`Project` · ★7 · keltokhy · `Py`</sub>

- **[jev-document-classification](https://github.com/Charlyhno-eng/jev-document-classification)** — JEV Document Classification enables the rapid and cost-effective classification of text-based documents using AI, leveraging TypeSafe's "System One" model.
  <sub>`Project` · ★6 · charlyhno-eng · `TS`</sub>

- **[jev-for-engineers](https://github.com/Foadsf/jev-for-engineers)** — Eight minimal working examples of TypeSafe's Jev (a System One model) applied to mechanical and electrical engineering: CAD/CAE/CAM routing, FEM result triage, DFM screening, BOM alignment, hallucination-proof extraction. Zero dependencies.
  <sub>`Project` · ★6 · foadsf · `Py`</sub>

- **[jev-skip](https://github.com/valentynkit/jev-skip)** — Skips video sponsor segments by reading the captions and deciding at watch time.
  <sub>`Project` · ★6 · valentynkit · `TS`</sub>

- **[jev-ids](https://github.com/jev-sec/jev-ids)** — Blazing-Fast Token-Efficient Intrusion Detection System (IDS) based on TypeSafe's Jev
  <sub>`Project` · ★5 · jev-ids · `Py`</sub>

- **[jev-linkedin-slop-filter](https://github.com/Arpit-Khandelwal/jev-linkedin-slop-filter)** — Slams a BAIT, CORP or BRAG stamp onto LinkedIn engagement-bait, judged live by Jev (TypeSafe System One).
  <sub>`Project` · ★5 · arpit-khandelwal · `JS`</sub>

- **[jev-triage](https://github.com/cephalization/jev-triage)** — Uses typeful jev, zero sync to pull and sync large repositories for issue triage
  <sub>`Project` · ★5 · cephalization · `TS`</sub>

- **[jeveryword](https://github.com/jkrup/jeveryword)** — Text extraction with Jev: field extraction, PII detection and exact quotes, built on TypeSafe's Jev.
  <sub>`Project` · ★5 · jkrup · `JS`</sub>

- **[mysql-ailike](https://github.com/maayanlevy/mysql-ailike)** — Natural-language row filtering for MySQL, powered by TypeSafe Jev.
  <sub>`Plugin` · ★5 · maayanlevy · `C++`</sub>

- **[n8n-nodes-jev-classification](https://github.com/khmuhtadin/n8n-nodes-jev-classification)** — n8n community node for Jev by TypeSafe AI: classify, score and check text with calibrated probabilities. Parallel requests and multi-item batching.
  <sub>`Project` · ★5 · khmuhtadin · `TS`</sub>

- **[tab-bouncer](https://github.com/MANISH007700/tab-bouncer)** — Chrome extension that closes the tabs you don't need, judged by TypeSafe's Jev in one call. Tell it what you're doing; it shows the rest the door.
  <sub>`Plugin` · ★5 · manish007700 · `JS`</sub>

- **[agi-jev-containment](https://github.com/carlosedm10/agi-jev-containment)** — AGI JEV Detection — local AI agent monitor: chain-level malicious-agent detection (TypeSafe Jev + Sentinel), escalate-only L1–L5 containment, Neo4j forensics, AngryRobot dashboard. HackSpain 2026.
  <sub>`Project` · ★4 · carlosedm10 · `Py` · ⚠ `no licence`</sub>

- **[discoprint](https://github.com/lirantal/discoprint)** — Classify an artist's discography by theme, mood, and lyrical complexity with Jev (TypeSafe AI), and view it as a colorful terminal dashboard
  <sub>`Project` · ★4 · lirantal · `JS`</sub>

- **[hunch](https://github.com/steven-shoemaker/hunch)** — Ask Jev over columns of data: closed-set questions, cached and joined back.
  <sub>`Project` · ★4 · steven-shoemaker · `Py`</sub>

- **[jev-mail](https://github.com/muhammedilyasy/jev-mail)** — Chrome extension that triages Gmail with TypeSafe's Jev model: category, priority, spam % and reply % on every email.
  <sub>`Plugin` · ★4 · muhammedilyasy · `JS`</sub>

- **[jev-pr-labeler](https://github.com/1jehuang/jev-pr-labeler)** — Semantic GitHub PR labels using Jev's typed decisions, with conceptual scope instead of line counts
  <sub>`Project` · ★4 · 1jehuang · `Py`</sub>

- **[notiq](https://github.com/chengyongru/notiq)** — Native Android notification filtering with natural-language rules, powered by Jev or self-hosted FastJev.
  <sub>`Project` · ★4 · chengyongru · `Kt` · ⚠ `no licence`</sub>

- **[agent-fastpath](https://github.com/abhishekswe/agent-fastpath)** — Jev MCP server: a decision layer for coding agents, built on TypeSafe Jev (System One model). Ship gates, risk checks, file triage that keeps files out of context, and a safe headless browser, with calibrated confidence. For Claude Code, Codex, Cursor.
  <sub>`Plugin` · ★3 · abhishekswe · `TS`</sub>

- **[dsh-jev-decide](https://github.com/nanami-0713/dsh-jev-decide)** — DSH plugin: register TypeSafe Jev (System One decision model) as an agent tool — jev_decide returns calibrated probabilities (noul/choice/score) for routing/triage/guardrail judgments, no text generation. 把 TypeSafe Jev 决策模型注册为 DSH agent 工具
  <sub>`Plugin` · ★3 · nanami-0713 · `JS`</sub>

- **[Jev by Example](https://github.com/ReallyArtificial/jev-by-example)** — Ten runnable JavaScript agent decisions, one file each: reconciling a new memory against a stored one, gating whether an HTTP 200 really satisfied the task, retry vs. reconcile after an uncertain write, scoring context against a budget, checking a handoff for dropped prohibitions.
  <sub>`Project` · ★3 · Really Artificial · `JS` · `choice` · `score` · `noul` · ⚠ `one commit` `AI-written`</sub>

- **[jev-mcp-server](https://github.com/wangkuangkuang/jev-mcp-server)** — MCP server for Jev (TypeSafe System One): the three official question types — choice, score, noul — plus batch classify. Calibrated probabilities, ~0.5s, <$0.001/call.
  <sub>`Plugin` · ★3 · wangkuangkuang · `Py`</sub>

- **[jev-research-pipeline](https://github.com/shimo4228/jev-research-pipeline)** — Daily research monitor for standing questions: deterministic Python owns the loop, TypeSafe Jev screens sources per question, Qwen writes the notes (pilot)
  <sub>`Project` · ★3 · shimo4228 · `Py`</sub>

- **[jev-secret-detection](https://github.com/teyhouse/jev-secret-detection)** — Measures how well TypeSafe's RLCD-Jev model spots real secret credentials in file snippets
  <sub>`Benchmark` · ★3 · teyhouse · `Py` · ⚠ `no licence`</sub>

- **[jev-slop-guard](https://github.com/davertor/jev-slop-guard)** — Jev Slop Guard — a Chrome extension that scores and stamps AI slop on your X and LinkedIn feeds as you scroll
  <sub>`Plugin` · ★3 · davertor · `JS`</sub>

- **[jevticktrouter](https://github.com/GhrezaKh74/JevTicktRouter)** — A .NET 10 and React 19 application for fast, structured AI-powered ticket triage using TypeSafe Jev.
  <sub>`Project` · ★3 · ghrezakh74 · `C#` · ⚠ `no licence`</sub>

- **[guard-jev](https://github.com/NorbertBodziony/guard-jev)** — A text-moderation demo: one systemOne call screens seven Noul hazards and one severity Score in parallel, and the verdict is computed in code from policy thresholds.
  <sub>`Project` · ★2 · norbertbodziony · `TS` · ⚠ `no licence`</sub>

- **[hush](https://github.com/emreozyoruk/hush)** — Issue triage that stays quiet when it isn't sure. Calibrated labels, spam and duplicate detection — with abstention.
  <sub>`Project` · ★2 · emreozyoruk · `JS`</sub>

- **[jev-chess](https://github.com/hemanth/jev-chess)** — Chess moves, evaluations, persona opponents, and game classification with TypeSafe AI System One
  <sub>`Project` · ★2 · hemanth · `TS` · ⚠ `no licence`</sub>

- **[jev-clean](https://github.com/Kunyanli230/jev-clean)** — decision-first data cleaning system powered by Jev
  <sub>`Project` · ★2 · kunyanli230 · `Py`</sub>

- **[jev-mode](https://github.com/ddfeyes/jev-mode)** — I kept watching coding agents burn context on decisions that aren't hard - triage 400 tickets, tag 600 files, route to one of six teams. jev-mode moves those verdicts to a typed-judgment model. I A/B'd it: 78% fewer tokens, 16x less work-attributable input, accuracy 96.1% vs 93.7%. Python, no d
  <sub>`Project` · ★2 · ddfeyes · `Py`</sub>

- **[jev-organize](https://github.com/nexibeo/jev-organize)** — Throw in a pile of company files and get them classified and organized by department, type, sensitivity, date, counterparty and PII, with an index for AI agents. Powered by TypeSafe's Jev on OpenRouter (17¢ per 1,000 files). Zero-dependency Node CLI + Claude skill + Codex agent.
  <sub>`Plugin` · ★2 · nexibeo · `JS`</sub>

- **[jev-playwright-mcp](https://github.com/krw82/jev-playwright-mcp)** — Jev-augmented Playwright MCP proxy — page-state triage, prompt-injection shielding, goal-based snapshot pruning, risky-action gating. Drop-in wrapper around @playwright/mcp for any coding agent.
  <sub>`Plugin` · ★2 · krw82 · `TS`</sub>

- **[jev-resilience](https://github.com/Vicente-MD/jev-resilience)** — Non-blocking Spring Boot Starter for Spring WebFlux that implements a Semantic Circuit Breaker to detect silent HTTP 200 failures using TypeSafe Jev.
  <sub>`Plugin` · ★2 · vicente-md · `Java` · ⚠ `no licence`</sub>

- **[jev-review-action](https://github.com/fatwang2/jev-review-action)** — Configurable GitHub submission review and PR classification with TypeSafe Jev. No text-generation model.
  <sub>`Project` · ★2 · fatwang2 · `JS`</sub>

- **[metis](https://github.com/Ayush0054/metis)** — Metis: automatic GitHub issue triage powered by TypeSafe AI Jev. A reusable GitHub Action.
  <sub>`Project` · ★2 · ayush0054 · `Py`</sub>

- **[pulselane](https://github.com/ndolinschi/pulselane)** — PulseLane — clinic triage decisions via TypeSafe Jev
  <sub>`Project` · ★2 · ndolinschi · `TS` · ⚠ `no licence`</sub>

- **[triagedy](https://github.com/m0rphtail/triagedy)** — Alert triage as a UNIX filter: JSONL security alerts in, typed decisions out. Runs on TypeSafe Jev or a local model; policy routing stays in code.
  <sub>`Project` · ★2 · m0rphtail · `Rs`</sub>

- **[watfile](https://github.com/jexp/watfile)** — Text/PDF - File categorization and sorting with Typesafe AI Jev or local calibrated decision model
  <sub>`Project` · ★2 · jexp · `Py` · ⚠ `no licence`</sub>

- **[zerosweep](https://github.com/sysadarsh/zerosweep)** — Autonomous System-One Triage Engine & Benchmark powered by TypeSafe AI (Jev). 75ms inference, $0 output tokens, and RLCD epistemic safety gates.
  <sub>`Benchmark` · ★2 · sysadarsh · `TS` · ⚠ `no licence`</sub>

- **[himalaya-jev-mail-classify](https://github.com/initrd/himalaya-jev-mail-classify)** — Label and prioritise Gmail with a language model. Reads mail through himalaya, classifies each thread with Jev (TypeSafe) over OpenRouter, and applies Gmail labels and colours. Dry run by default, idempotent, no state file.
  <sub>`Project` · ★1 · initrd · `Py`</sub>

- **[jev-benchmark](https://github.com/themsquared/jev-benchmark)** — Reproducible benchmark for TypeSafe AI's Jev on agent tool-call risk classification: accuracy, latency, and whether the confidence score is worth routing on.
  <sub>`Benchmark` · ★1 · themsquared · `Py`</sub>

- **[jev-eval](https://github.com/4esv/jev-eval)** — Benchmark TypeSafe Jev against any OpenRouter model on your own labelled classification data: accuracy, calibration, latency, cost
  <sub>`Benchmark` · ★1 · 4esv · `Py` · ⚠ `no licence`</sub>

- **[jev-eval](https://github.com/onlyoneaman/jev-eval)** — TypeSafe's Jev vs gpt-5.4-mini and gpt-5.6-luna on four public classification sets: cases, per-item answers, scoring, charts
  <sub>`Benchmark` · ★1 · onlyoneaman · `TS`</sub>

- **[jev-issue-radar](https://github.com/Patrick-SCH03/jev-issue-radar)** — GitHub issue triage with side-by-side evidence. Try the public sample without setup, or run the local app with TypeSafe Jev via OpenRouter.
  <sub>`Project` · ★1 · patrick-sch03 · `JS`</sub>

- **[jev-logtriage](https://github.com/jyatesdotdev/jev-logtriage)** — Jev decides whether a batch of logs is worth acting on. Typed questions, confidence gates, nothing executed.
  <sub>`Project` · ★1 · jyatesdotdev · `Py`</sub>

- **[jev-screen-mcp](https://github.com/jiawei686/jev-screen-mcp)** — Single-purpose MCP server (one tool, one job): a content-moderation gate powered by TypeSafe Jev (System One decision model).
  <sub>`Plugin` · ★1 · jiawei686 · `TS`</sub>

- **[jev-trace-classifier](https://github.com/sypherin/jev-trace-classifier)** — Application of TypeSafe Jev (noul judgment primitive) on the collusion.wiki corpus: agent vs human page authorship, head-to-head vs local Qwen3.8-Flash-Next
  <sub>`Benchmark` · ★1 · sypherin · `Py`</sub>

- **[Jevatar](https://github.com/AppChainAI/Jevatar)** — An AI companion that replies only with facial expressions. Jev (TypeSafe System One) judges your message and picks 1 of 14 moods; blobatar morphs its face. React + Vite + Bun.
  <sub>`Project` · ★1 · appchainai · `TS`</sub>

- **[jevmod](https://github.com/ohernandezdev/jevmod)** — Moderation for communities and apps, powered by Jev (TypeSafe): probabilities per category, thresholds you own. Discord/Telegram/Reddit bots, CLI, Python, npm, HTTP API, MCP.
  <sub>`Plugin` · ★1 · ohernandezdev · `Py`</sub>

- **[jevtriage](https://github.com/sathariels/jevtriage)** — GitHub Action + CLI: triage PRs with TypeSafe Jev (ready / needs review / risky) with confidence gates and jevcheck-friendly contracts.
  <sub>`Project` · ★1 · sathariels · `Py`</sub>

- **[omp-jevens-classifier](https://github.com/STRML/omp-jevens-classifier)** — Jev-powered model-judged permission gate for OMP (TypeSafe System One)
  <sub>`Project` · ★1 · strml · `TS` · ⚠ `archived`</sub>

- **[progressgate](https://github.com/AshutoshVJTI/progressgate)** — Detect semantic stagnation in AI agent loops
  <sub>`Project` · ★1 · ashutoshvjti · `TS`</sub>

- **[typesafe-image-diffusion](https://github.com/Wizhill05/typesafe-image-diffusion)** — Diffusion-style pixel art out of a general classifier (TypeSafe Jev): 256 parallel pixel questions + refinement passes
  <sub>`Project` · ★1 · wizhill05 · `TS` · ⚠ `no licence`</sub>

- **[typesafe-triage-guard](https://github.com/shivam2003-dev/typesafe-triage-guard)** — Three composable judgment pipelines on TypeSafe's Jev: support-ticket triage, observability alert triage, and a deploy-risk gate.
  <sub>`Project` · ★1 · shivam2003-dev · `Py`</sub>

- **[github-issue-classification-using-jev](https://github.com/KalyanM45/GitHub-Issue-Classification-Using-Jev)** — This repository contains a GitHub issue classifier built on Jev, TypeSafe AI's System One model. It labels every new issue with typed values and calibrated confidence in milliseconds, labelling what it is sure about and escalating what it is not. Three guardrail layers guard every write, and a
  <sub>`Project` · ★0 · kalyanm45 · `Py`</sub>

- **[jev-agent-skill](https://github.com/yuyang2230/jev-agent-skill)** — Free typed judgments for AI agents: offload classify/screen/score/verify to Jev (TypeSafe System One) via OpenCode Zen. Claude Code / ZCode skill. 给AI代理省token的免费决策分流技能
  <sub>`Plugin` · ★0 · yuyang2230 · `Py`</sub>

- **[jev-labeler-action](https://github.com/yamadashy/jev-labeler-action)** — Zero-config AI issue labeling with TypeSafe's Jev. No generated text. Unofficial.
  <sub>`Project` · ★0 · yamadashy · `TS`</sub>

- **[JevEye](https://github.com/Adityakhalkar/JevEye)** — Ask Jev about an image. A CNN reports what it sees with a calibrated confidence or an abstention; Jev judges what it means.
  <sub>`Project` · ★0 · adityakhalkar · `TS`</sub>

- **[An early-access test of TypeSafe's Jev: calibrated judgments for half a cent](https://lindfors.no/blog/a-first-look-at-typesafes-jev/)** — The best independent test found: 24 Norwegian documents on one pinned model version, opening with a case the model got wrong while correctly reporting low confidence.
  <sub>`Benchmark` · Lindfors</sub>

- **[Jev - The Ultimate Classification Model?](https://youtube.com/watch?v=X117w2Rark8)** — An ML engineer's walkthrough from the classification-task angle, which is the framing closest to what the model actually does.
  <sub>`Video` · Sam Witteveen</sub>

- **[jevai.org community showcase cases](https://www.jevai.org/cases)** — Nine worked community scenarios: intent routing, invoice classification, news filtering, product tagging, moderation, claim verification, CSV validation and more.
  <sub>`Project` · ⚠ `unverified claims`</sub>

- **[Testing TypeSafe Jev, Mistral and Gemini for local event validation](https://nearhere.events/blog/typesafe-jev-mistral-gemini-event-validation)** — The only three-way head-to-head found, with each model's prompt tuned separately and the scope limited to one task rather than a general ranking.
  <sub>`Benchmark` · Near Here</sub>

---

<sub>Generated from `catalog.json` by `scripts/build_readme.py`. Edit the catalogue, not this file — CI fails if the two disagree.</sub>
