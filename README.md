<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Kapil%20Rathore&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Open%20Source%20Analyst%20%7C%20Bug%20Hunter%20%7C%20OSS%20Contributor&descAlignY=58&descColor=a0a0ff" width="100%"/>

</div>

<br/>

<div align="center">

[![Repos Analyzed](https://img.shields.io/badge/Repos%20Analyzed-35+-0f0c29?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![Issues & PRs Opened](https://img.shields.io/badge/Issues%20%26%20PRs%20Opened-42+-302b63?style=for-the-badge&logo=git-pull-request&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![PRs Merged by Maintainers](https://img.shields.io/badge/PRs%20Merged-15-2ea44f?style=for-the-badge&logo=git-merge&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![Stars Impacted](https://img.shields.io/badge/Stars%20Impacted-750K+-f0a500?style=for-the-badge&logo=star&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![Biggest Merge](https://img.shields.io/badge/Biggest%20Merge-n8n%20194K%20stars-f59e0b?style=for-the-badge&logo=git-merge&logoColor=white)](https://github.com/n8n-io/n8n/pull/32801)
[![Release Notes](https://img.shields.io/badge/Named%20In%20Release%20Notes-CodeceptJS%20v4.0.8-7c3aed?style=for-the-badge&logo=trophy&logoColor=white)](https://github.com/codeceptjs/CodeceptJS/releases/tag/4.0.8)

</div>

---

## 👋 About Me

I do deep commit-level analysis on actively maintained open source projects — looking for behavioral contract changes that slip past code review: silent return value mutations, exception scope widening, broken caller assumptions, wrong entity types in API calls.

When I find something real, I report it with a reproducible description and a suggested fix.

> Full writeups with code → **[oss-findings](https://github.com/kapil971390/oss-findings)**

---

## 📋 All Activity

<div align="center">

| Date | Repo | What | Severity | Status |
|:-----|:-----|:-----|:--------:|:------:|
| Jul 1 | [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | [PR #925](https://github.com/NanmiCoder/MediaCrawler/pull/925) — `IpProxyProvider.get()` returns `None` for unknown provider names — silently stored, crashes later with `AttributeError: 'NoneType' object has no attribute 'get_proxy'` — labeled `bug` + `lgtm` by NanmiCoder | 🟡 Medium | ✅ [Merged](https://github.com/NanmiCoder/MediaCrawler/pull/925) |
| Jul 1 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | [PR #227](https://github.com/calesthio/OpenMontage/pull/227) — `success` contract mismatch in `CharacterAnimationReviewer` — diverged from `visual_qa.py` sibling pattern — merged by calesthio | 🟡 Medium | ✅ [Merged](https://github.com/calesthio/OpenMontage/pull/227) |
| Jul 1 | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) | [PR #5208](https://github.com/opendatalab/MinerU/pull/5208) — `persist_downloaded_model_config` silently swallows write failures — model downloaded but path not saved — MinerU re-downloads on every new session | 🟡 Medium | ⏳ [Open](https://github.com/opendatalab/MinerU/pull/5208) |
| Jun 29 | [n8n-io/n8n](https://github.com/n8n-io/n8n) ⭐ **194K** | [PR #32801](https://github.com/n8n-io/n8n/pull/32801) — IPv6 `[::1]` missing from MCP redirect URI DTO — admin gets HTTPS-required error even though runtime accepts it — merged by nikhilkuria — **BIGGEST REPO YET** | 🟡 Medium | ✅ [Merged](https://github.com/n8n-io/n8n/pull/32801) |
| Jun 29 | [denoland/deno](https://github.com/denoland/deno) ⭐ 100K+ | [PR #35520](https://github.com/denoland/deno/pull/35520) — `BTreeSet::contains` byte-exact match misses case-insensitive npm names in trust-policy — *"bug is real and your analysis is spot on"* — bartlomieju | 🔴 High | ✅ [Merged](https://github.com/denoland/deno/pull/35520) |
| Jun 26 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [PR #1078](https://github.com/harry0703/MoneyPrinterTurbo/pull/1078) — `youtube_shorts` platform name mismatch — metadata silently dropped on upload | 🟡 Medium | ✅ [Merged](https://github.com/harry0703/MoneyPrinterTurbo/pull/1078) |
| Jun 25 | [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro) | [PR #150](https://github.com/palmier-io/palmier-pro/pull/150) — `CFTypeID` guard missing before force cast — fatal crash on XMEML export | 🔴 High | ✅ [Merged](https://github.com/palmier-io/palmier-pro/pull/150) |
| Jun 22 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [PR #1065](https://github.com/harry0703/MoneyPrinterTurbo/pull/1065) — `match_materials_to_script` missing from REST DTO — chronological term gen unreachable via API | 🟡 Medium | ✅ [Merged](https://github.com/harry0703/MoneyPrinterTurbo/pull/1065) |
| Jun 22 | [bytedance/deer-flow](https://github.com/bytedance/deer-flow) ⭐ 75K (ByteDance) | [PR #3714](https://github.com/bytedance/deer-flow/pull/3714) — `_lock` defined but never acquired in token budget — data race on concurrent runs — merged by WillemJiang — **v2.1.0 release note upcoming** | 🔴 High | ✅ [Merged](https://github.com/bytedance/deer-flow/pull/3714) |
| Jun 21 | [krillinai/KrillinAI](https://github.com/krillinai/KrillinAI) | [PR #297](https://github.com/krillinai/KrillinAI/pull/297) — Path traversal: API keys readable via `/api/file/config/config.toml` | 🔴 Critical | ✅ [Merged](https://github.com/krillinai/KrillinAI/pull/297) |
| Jun 18 | [affaan-m/ECC](https://github.com/affaan-m/ECC) ⭐ 217K | [PR #2292](https://github.com/affaan-m/ECC/pull/2292) — `find -exec rm` bypass via compound commands (`&&` `;` `|` `||`) in gateguard security hook | 🔴 High | ✅ [Merged](https://github.com/affaan-m/ECC/pull/2292) |
| Jun 18 | [penpot/penpot](https://github.com/penpot/penpot) | [#10279](https://github.com/penpot/penpot/issues/10279) — Stale MCP token shown after regeneration — merged same day into v2.17.0 | 🟡 Medium | ✅ [Merged in v2.17.0](https://github.com/penpot/penpot/pull/10280) |
| Jun 16 | [magento/magento2](https://github.com/magento/magento2) | [#40882](https://github.com/magento/magento2/issues/40882) — `NoSuchEntityException` race in `InvalidSkuProcessor` bulk price API | 🔴 High | ⏳ [PR #40883](https://github.com/magento/magento2/pull/40883) |
| Jun 14 | [midjourney-api](https://github.com/erictik/midjourney-api) | [#294](https://github.com/erictik/midjourney-api/issues/294) — `ChannelId` used as `ServerId` in guild API calls | 🔴 High | ⏳ Open |
| Jun 14 | [midjourney-api](https://github.com/erictik/midjourney-api) | [#295](https://github.com/erictik/midjourney-api/issues/295) — Dead code in `cacheCommand()` — cache never populated | 🟡 Medium | ⏳ Open |
| Jun 13 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [PR #1033](https://github.com/harry0703/MoneyPrinterTurbo/pull/1033) — CLI local source validation gaps | 🟡 Medium | ✅ [Merged](https://github.com/harry0703/MoneyPrinterTurbo/pull/1033) |
| Jun 10 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [#1013](https://github.com/harry0703/MoneyPrinterTurbo/issues/1013) — Groq model unvalidated on list-fetch failure | 🟡 Medium | ✅ [Fixed PR #1014](https://github.com/harry0703/MoneyPrinterTurbo/pull/1014) |
| Jun 5 | [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) | [PR #5639](https://github.com/codeceptjs/CodeceptJS/pull/5639) — `--shuffle` flag silently ignored after commit #5438 — named in v4.0.8 release notes | 🔴 High | ✅ [Merged](https://github.com/codeceptjs/CodeceptJS/pull/5639) |
| Jun 4 | [medusajs/medusa](https://github.com/medusajs/medusa) | [Discussion #15550](https://github.com/medusajs/medusa/discussions/15550) — Race condition in `compensatePaymentIfNeededStep` | 🔴 High | 👀 Watching |
| Jun 4 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [#984](https://github.com/harry0703/MoneyPrinterTurbo/issues/984) — Qwen empty `choices[]` unhandled crash | 🔴 High | ✅ [Fixed PR #994](https://github.com/harry0703/MoneyPrinterTurbo/pull/994) |
| Jun 26 | [questdb/questdb](https://github.com/questdb/questdb) | [PR #7336](https://github.com/questdb/questdb/pull/7336) — `regr_r2()` returns NaN for large-magnitude inputs — intermediate overflow in denominator | 🟡 Medium | ⏳ Open |
| Jun 26 | [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | [PR #1785](https://github.com/ZhuLinsen/daily_stock_analysis/pull/1785) — Short credentials (<32 chars) not redacted in diagnostic output | 🔴 High | ⏳ Open |
| Jun 22 | [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) | [PR #13835](https://github.com/ohmyzsh/ohmyzsh/pull/13835) — `branch_size` computed before `%→%%` escaping — padding off by N spaces | 🟡 Medium | ⏳ Open |

</div>

---

## 🔭 Repos Analyzed

<div align="center">

| Repository | Language | Stars | Finding |
|:-----------|:---------|------:|:--------|
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | TypeScript | 194K+ | IPv6 loopback missing from MCP DTO — merged ✅ |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | JavaScript | 217K+ | Security bypass in gateguard hook — merged ✅ |
| [denoland/deno](https://github.com/denoland/deno) | Rust | 100K+ | Case-insensitive npm trust-policy match — merged ✅ |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | Python | 75K+ | Data race in token budget `_lock` — merged ✅ |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Python | 89K+ | 5 bugs found, 5 fixed ✅ |
| [penpot/penpot](https://github.com/penpot/penpot) | ClojureScript | 50K+ | Stale MCP token state — merged in v2.17.0 ✅ |
| [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | Python | 6K+ | `None` proxy provider crash — labeled lgtm, merged ✅ |
| [opendatalab/MinerU](https://github.com/opendatalab/MinerU) | Python | 30K+ | Silent config persist failure — PR open ⏳ |
| [grafana/grafana](https://github.com/grafana/grafana) | Go/TypeScript | 65K+ | Analyzed — cascade delete, NATS publisher |
| [usestrix/strix](https://github.com/usestrix/strix) | Python | — | Analyzed — telemetry + RateLimitError handling |
| [medusajs/medusa](https://github.com/medusajs/medusa) | TypeScript | 28K+ | Race condition in async workflow step |
| [erictik/midjourney-api](https://github.com/erictik/midjourney-api) | TypeScript | 1.8K | 2 bugs found — ChannelId/ServerId mismatch |
| [magento/magento2](https://github.com/magento/magento2) | PHP | 14K+ | `NoSuchEntityException` race in bulk price API |
| [bagisto/bagisto](https://github.com/bagisto/bagisto) | PHP | 9.1K+ | 2 security claims — defended upstream |
| [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) | JavaScript | 10K+ | `--shuffle` regression — named in v4.0.8 release ✅ |
| [krillinai/KrillinAI](https://github.com/krillinai/KrillinAI) | Go | 3K+ | Path traversal security fix — merged ✅ |
| [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro) | Swift | — | CFTypeID crash fix — merged ✅ |
| [questdb/questdb](https://github.com/questdb/questdb) | Java | 15K+ | `regr_r2()` NaN overflow — PR open ⏳ |
| [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) | Shell | 175K+ | `%` escaping bug in josh theme — PR open ⏳ |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | Python | — | Success contract mismatch — merged ✅ |
| [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | Python | — | Credential redaction gap — PR open ⏳ |
| [apple/container](https://github.com/apple/container) | Swift | 12K+ | `try!` crash fix — valid, duplicate of earlier PR |
| [flutter/flutter](https://github.com/flutter/flutter) | Dart | 170K+ | Windows engine null guard — analyzed |
| [syncthing/syncthing](https://github.com/syncthing/syncthing) | Go | 67K+ | Symlink traversal — analyzed |

</div>

---

## 📈 Stats

```
Issues Opened     ██████████  22+
PRs Submitted     ██████████  20+
PRs Merged        ██████████  15  ← accepted by maintainers
Stars Impacted    ██████████  750K+
Repos Analyzed    ██████████  35+
Confirmed Bugs    ██████████  18+
Biggest Merge     ██████████  n8n — 194K stars 🏆
Named in Release  █░░░░░░░░░  1   ← CodeceptJS v4.0.8
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
