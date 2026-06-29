<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Kapil%20Rathore&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Open%20Source%20Analyst%20%7C%20Bug%20Hunter%20%7C%20OSS%20Contributor&descAlignY=58&descColor=a0a0ff" width="100%"/>

</div>

<br/>

<div align="center">

[![Repos Analyzed](https://img.shields.io/badge/Repos%20Analyzed-29+-0f0c29?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![Issues & PRs Opened](https://img.shields.io/badge/Issues%20%26%20PRs%20Opened-35+-302b63?style=for-the-badge&logo=git-pull-request&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![PRs Merged by Maintainers](https://img.shields.io/badge/PRs%20Merged-13-2ea44f?style=for-the-badge&logo=git-merge&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![Stars Impacted](https://img.shields.io/badge/Stars%20Impacted-1.3M+-f0a500?style=for-the-badge&logo=star&logoColor=white)](https://github.com/kapil971390/oss-findings)
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
| Jun 29 | [n8n-io/n8n](https://github.com/n8n-io/n8n) ⭐ **194K** | [PR #32801](https://github.com/n8n-io/n8n/pull/32801) — IPv6 `[::1]` missing from MCP redirect URI DTO — admin gets HTTPS-required error even though runtime accepts it — merged by nikhilkuria after internal review queue (~1 month, GHC-8773) — **BIGGEST REPO YET** | 🟡 Medium | ✅ [Merged](https://github.com/n8n-io/n8n/pull/32801) |
| Jun 29 | [denoland/deno](https://github.com/denoland/deno) ⭐ 100K+ | [PR #35520](https://github.com/denoland/deno/pull/35520) — `BTreeSet::contains` byte-exact match misses case-insensitive npm names in trust-policy — *"bug is real and your analysis is spot on"* — bartlomieju | 🔴 High | ✅ [Merged](https://github.com/denoland/deno/pull/35520) |
| Jun 26 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [PR #1078](https://github.com/harry0703/MoneyPrinterTurbo/pull/1078) — `youtube_shorts` platform name mismatch — metadata silently dropped on upload | 🟡 Medium | ✅ [Merged](https://github.com/harry0703/MoneyPrinterTurbo/pull/1078) |
| Jun 25 | [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro) | [PR #150](https://github.com/palmier-io/palmier-pro/pull/150) — CFTypeID guard missing — fatal crash on XMEML export | 🔴 High | ✅ [Merged](https://github.com/palmier-io/palmier-pro/pull/150) |
| Jun 22 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ⭐ 89K+ | [PR #1065](https://github.com/harry0703/MoneyPrinterTurbo/pull/1065) — `match_materials_to_script` missing from REST DTO — chronological term gen unreachable | 🟡 Medium | ✅ [Merged](https://github.com/harry0703/MoneyPrinterTurbo/pull/1065) |
| Jun 22 | [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | [PR #3714](https://github.com/bytedance/deer-flow/pull/3714) — `_lock` never acquired in token budget — data race on concurrent runs | 🔴 High | ✅ [Merged](https://github.com/bytedance/deer-flow/pull/3714) |
| Jun 21 | [krillinai/KrillinAI](https://github.com/krillinai/KrillinAI) | [PR #297](https://github.com/krillinai/KrillinAI/pull/297) — Path traversal: API keys readable via `/api/file/config/config.toml` | 🔴 Critical | ✅ [Merged](https://github.com/krillinai/KrillinAI/pull/297) |
| Jun 18 | [affaan-m/ECC](https://github.com/affaan-m/ECC) ⭐ 217K | [#2291](https://github.com/affaan-m/ECC/issues/2291) + [PR #2292](https://github.com/affaan-m/ECC/pull/2292) — `find -exec rm` bypass via compound commands (`&&` `;` `\|` `\|\|`) in gateguard security hook — triggered maintainer's GHSA-4v57 security advisory | 🔴 High | ✅ [Merged](https://github.com/affaan-m/ECC/pull/2292) |
| Jun 18 | [penpot/penpot](https://github.com/penpot/penpot) | [#10279](https://github.com/penpot/penpot/issues/10279) — Stale MCP token shown after regeneration — old token persisted in client state after server-side deletion | 🟡 Medium | ✅ [Merged in v2.17.0](https://github.com/penpot/penpot/pull/10280) |
| Jun 16 | [magento/magento2](https://github.com/magento/magento2) | [#40882](https://github.com/magento/magento2/issues/40882) — `NoSuchEntityException` race in `InvalidSkuProcessor` bulk price API | 🔴 High | ⏳ [PR #40883](https://github.com/magento/magento2/pull/40883) |
| Jun 5 | [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) | [PR #5639](https://github.com/codeceptjs/CodeceptJS/pull/5639) — `--shuffle` flag silently ignored after commit #5438 | 🔴 High | ✅ [Merged](https://github.com/codeceptjs/CodeceptJS/pull/5639) |
| Jun 14 | [midjourney-api](https://github.com/erictik/midjourney-api) | [#294](https://github.com/erictik/midjourney-api/issues/294) — `ChannelId` used as `ServerId` in guild API | 🔴 High | ⏳ Open |
| Jun 14 | [midjourney-api](https://github.com/erictik/midjourney-api) | [#295](https://github.com/erictik/midjourney-api/issues/295) — Dead code in `cacheCommand()`, cache never populated | 🟡 Medium | ⏳ Open |
| Jun 14 | [bagisto/bagisto](https://github.com/bagisto/bagisto) | [#11338](https://github.com/bagisto/bagisto/issues/11338) — `getClientOriginalName()` path traversal in `RMAImageRepository` — incomplete security fix | 🔴 Critical | ⏳ Open |
| Jun 14 | [bagisto/bagisto](https://github.com/bagisto/bagisto) | [#11339](https://github.com/bagisto/bagisto/issues/11339) — `v-html` XSS in Shop views — `product_name` + datagrid columns unescaped | 🔴 High | ⏳ Open |
| Jun 13 | [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | [PR #1033](https://github.com/harry0703/MoneyPrinterTurbo/pull/1033) — CLI local source validation fix | 🟡 Medium | ✅ [Merged](https://github.com/harry0703/MoneyPrinterTurbo/pull/1033) |
| Jun 10 | [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | [#1013](https://github.com/harry0703/MoneyPrinterTurbo/issues/1013) — Groq model unvalidated on list-fetch failure | 🟡 Medium | ✅ [Fixed PR #1014](https://github.com/harry0703/MoneyPrinterTurbo/pull/1014) |
| Jun 4 | [medusajs/medusa](https://github.com/medusajs/medusa) | [Discussion #15550](https://github.com/medusajs/medusa/discussions/15550) — Race condition in `compensatePaymentIfNeededStep` | 🔴 High | 👀 Watching |
| Jun 4 | [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | [#985](https://github.com/harry0703/MoneyPrinterTurbo/issues/985) — `>=` comparison risk in duration check | 🟡 Medium | 👀 Community PR expected |
| Jun 4 | [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | [#984](https://github.com/harry0703/MoneyPrinterTurbo/issues/984) — Qwen empty `choices[]` — unhandled crash | 🔴 High | ✅ [Fixed PR #994](https://github.com/harry0703/MoneyPrinterTurbo/pull/994) |
| Jun 4 | [Understand-Anything](https://github.com/Lum1104/Understand-Anything) | Discussion — commit analysis findings | 🟡 Medium | 👀 Watching |

</div>

---

## 🔭 Repos Analyzed

<div align="center">

| Repository | Language | Stars | Finding |
|:-----------|:---------|------:|:--------|
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | JavaScript | 217K+ | Security bypass in gateguard hook — `find -exec rm` via `&&`/`;`/`\|`/`\|\|` — merged ✅ |
| [penpot/penpot](https://github.com/penpot/penpot) | ClojureScript | 50K+ | Stale MCP token state — merged in v2.17.0 ✅ |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Python | 89K+ | 3 bugs found, 3 fixed |
| [medusajs/medusa](https://github.com/medusajs/medusa) | TypeScript | 28K+ | Race condition in async workflow step |
| [erictik/midjourney-api](https://github.com/erictik/midjourney-api) | TypeScript | 1.8K | 2 bugs found |
| [apify/crawlee-python](https://github.com/apify/crawlee-python) | Python | 9K+ | Silent URL filtering behavior change |
| [tox-dev/tox](https://github.com/tox-dev/tox) | Python | 4K+ | Config override namespace risk |
| [gptme/gptme](https://github.com/gptme/gptme) | Python | 4K+ | LLM routing logic analysis |
| [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything) | Python | — | Commit analysis findings |
| [acacode/swagger-typescript-api](https://github.com/acacode/swagger-typescript-api) | TypeScript | 4K+ | Analyzed — no actionable findings |
| [bagisto/bagisto](https://github.com/bagisto/bagisto) | PHP | 9.1K+ | 2 security bugs found |
| [aws/aws-sam-cli](https://github.com/aws/aws-sam-cli) | Python | 6.7K | Analyzed — no actionable findings |
| [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) | JavaScript | 10K+ | shuffle regression — PR #5639 merged ✅ |
| [magento/magento2](https://github.com/magento/magento2) | PHP | 14K+ | `NoSuchEntityException` race condition in bulk price API |

</div>

---

## 📈 Stats

```
Issues Opened     ██████████  20+
PRs Submitted     ████████░░  18+
PRs Merged        ████████░░  13  ← accepted by maintainers
Discussions       ██░░░░░░░░  2
Repos Analyzed    ██████████  29+
Confirmed Bugs    ██████████  15+
Biggest Merge     ██████████  n8n — 194K stars 🏆
Named in Release  █░░░░░░░░░  1   ← CodeceptJS v4.0.8
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
