<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Kapil%20Rathore&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Code%20Analysis%20%7C%20OSS%20Contributor%20%7C%20Bug%20Hunter&descAlignY=58&descColor=a0a0ff" width="100%"/>

</div>

<br/>

<div align="center">

[![Repos Analyzed](https://img.shields.io/badge/Repos%20Analyzed-8+-0f0c29?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![Bugs Confirmed](https://img.shields.io/badge/Bugs%20Confirmed-5-302b63?style=for-the-badge&logo=bugsnag&logoColor=white)](https://github.com/kapil971390/oss-findings)
[![PRs Merged](https://img.shields.io/badge/PRs%20Merged-2-24243e?style=for-the-badge&logo=git&logoColor=white)](https://github.com/kapil971390/oss-findings)

</div>

---

## 🔍 About

I analyze open-source repositories by examining recent commits for behavioral contract changes — things like silent return value mutations, exception scope widening, and broken caller assumptions that slip past code review.

When I find something real, I report it.

---

## 📋 Confirmed Findings

> Full writeups → **[oss-findings](https://github.com/kapil971390/oss-findings)**

<div align="center">

| Repository | Finding | Severity | Status |
|:-----------|:--------|:--------:|:------:|
| [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Qwen provider returns empty `choices[]` — silent crash with no diagnostic | 🔴 High | [✅ Fixed](https://github.com/harry0703/MoneyPrinterTurbo/pull/994) |
| [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Groq model name unvalidated on list-fetch failure — wrong model silently used | 🟡 Medium | [✅ Fixed](https://github.com/harry0703/MoneyPrinterTurbo/pull/1014) |
| [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | CLI `--video-source local` accepts invalid args without error until deep into run | 🟡 Medium | [⏳ PR Open](https://github.com/harry0703/MoneyPrinterTurbo/pull/1033) |
| [midjourney-api](https://github.com/erictik/midjourney-api) | `ChannelId` used as `ServerId` fallback — Discord guild API call fails silently | 🔴 High | 🔍 Reported |
| [midjourney-api](https://github.com/erictik/midjourney-api) | Dead code in `cacheCommand()` — `allCommand()` unreachable, cache never populated | 🟡 Medium | 🔍 Reported |

</div>

---

## 📊 Analysis Coverage

```
Python  ██████████████░░  8 repos
TypeScript  ██████░░░░░░░░░░  3 repos
JavaScript  ████░░░░░░░░░░░░  2 repos
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
