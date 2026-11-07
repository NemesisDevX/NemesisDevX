<div align="center">
  <a href="https://nemesisdevx.github.io/"><img src="./assets/nemesis-banner.svg" width="100%" alt="NEMESIS / Engineering — Abdelrahman Darwish" /></a>

  <h1>Abdelrahman Darwish <sub>· NemesisDevX</sub></h1>
  <p><strong>Flutter / Dart · Developer Tooling · Backend Engineering</strong></p>
  <p>Independent developer in Egypt. <strong>8 engineering PRs merged upstream</strong> into Flutter, Dart-Code and Apple-maintained Pkl tooling. One published Android app. Real code, regression tests and external reviews.</p>

  <p>
    <a href="https://nemesisdevx.github.io/"><strong>PORTFOLIO ↗</strong></a> &nbsp;·&nbsp;
    <a href="https://nemesisdevx.github.io/work.html"><strong>CASE STUDIES ↗</strong></a> &nbsp;·&nbsp;
    <a href="https://nemesisdevx.github.io/assets/Abdelrahman_Darwish_Engineering_CV_2026.pdf"><strong>RESUME (PDF) ↗</strong></a> &nbsp;·&nbsp;
    <a href="https://play.google.com/store/apps/details?id=com.tasbehati.ai.pr"><strong>ANDROID APP ↗</strong></a> &nbsp;·&nbsp;
    <a href="mailto:abdelrhmanmahrous386@gmail.com"><strong>EMAIL ↗</strong></a>
  </p>
  <p><sub>Available for paid remote engineering roles and contracts. Open-source contributions do not imply employment with upstream organizations.</sub></p>
</div>

---

### Engineering highlights · Start here

**01 — [Flutter Web accessibility](https://github.com/flutter/flutter/pull/195564)** · Corrected slider semantics when a disabled control becomes enabled. Regression-tested and merged into the Flutter engine.

**02 — [Dart-Code DTD lifecycle](https://github.com/Dart-Code/Dart-Code/pull/6349)** · Fixed leaked subscriptions, callbacks after disposal and unhandled asynchronous errors. Merged after review and regression coverage.

**03 — [Dart-Code CI test performance](https://github.com/Dart-Code/Dart-Code/pull/6373)** · Removed unnecessary real Dart/Flutter process spawns; a focused Flutter test group improved from ~24s to ~3s locally. Reviewed and merged.

<sub>Priority order: engineering impact, technical depth, test evidence and relevance to software engineering roles — not merge date.</sub>

---

## Merged upstream

**8 verified merged upstream engineering PRs as of 7 November 2026 — ranked by engineering impact, not chronology.** Real bug fixes and regression tests accepted after upstream review. Every link points to the corresponding public code, discussion, and merge record; contributions do not imply employment by the projects or their parent organizations.

| Contribution (ranked) | Engineering impact | Merged upstream |
| :--- | :--- | :--- |
| **01 / Flutter Core / Web Engine** | Fixed initial accessibility value/range synchronization when a previously disabled slider becomes enabled; reviewer-validated regression coverage | [flutter/flutter #195564](https://github.com/flutter/flutter/pull/195564) |
| **02 / Dart-Code / DTD lifecycle** | Fixed async event and service callbacks that could run after VS Code extension disposal; added regression coverage and responded to maintainer review | [Dart-Code #6349](https://github.com/Dart-Code/Dart-Code/pull/6349) |
| **03 / Dart-Code / CI performance** | Replaced unnecessary real Dart/Flutter process and network launches in command tests with deterministic stubs; focused Flutter test group improved ~24s to ~3s locally, with DanTup review and approval | [Dart-Code #6373](https://github.com/Dart-Code/Dart-Code/pull/6373) |
| **04 / Dart-Code / VS Code** | Fixed hidden ancestor directories breaking Dart test filtering and `pubspec.yaml` handling | [Dart-Code #6301](https://github.com/Dart-Code/Dart-Code/pull/6301) |
| **05 / Apple / pkl-neovim** | Corrected nested Pkl language-server settings and added a headless Neovim regression harness | [apple/pkl-neovim #75](https://github.com/apple/pkl-neovim/pull/75) |
| **06 / Dart-Code / SDK discovery** | Added SDK search-precedence tests, including Flutter, Fuchsia, PATH, and Bazel fallback; removed obsolete `DART_PATH_OVERRIDE` handling | [Dart-Code #6337](https://github.com/Dart-Code/Dart-Code/pull/6337) |
| **07 / Dart-Code / Package testing** | Expanded automated coverage for package commands and `pubspec.yaml` update guards, with maintainer-requested test isolation | [Dart-Code #6332](https://github.com/Dart-Code/Dart-Code/pull/6332) |
| **08 / Dart-Code / Project creation** | Added 12 tests for `dart.createProject`, SDK configuration, cancellation and error paths | [Dart-Code #6324](https://github.com/Dart-Code/Dart-Code/pull/6324) |

**Also merged (community, not counted above):** [CALLE-AI / awesome-phone-call-agents #600](https://github.com/CALLE-AI/awesome-phone-call-agents/pull/600) — an AI application listing added to a public community directory.

<sub>The Apple contribution is to an Apple-maintained open-source repository, not a claim of employment or affiliation. AI assistance was disclosed where applicable, and links provide the independently reviewable engineering evidence.</sub>

<p><a href="https://nemesisdevx.github.io/"><strong>↗ Explore NEMESIS / Engineering</strong></a> &nbsp; · &nbsp; <a href="mailto:abdelrhmanmahrous386@gmail.com?subject=Remote%20engineering%20opportunity">Discuss a paid remote role or contract</a></p>

## Engineering case studies — three merged, one human-approved

| What broke | Fix & validation | Public proof |
| :--- | :--- | :--- |
| **Flutter Web accessibility (merged):** enabling a previously disabled slider could leave incorrect initial screen-reader value/range attributes. | Corrected the Web semantics initialization path, added regression coverage, and incorporated reviewer feedback. Merged **4 Nov 2026**. | [Flutter #195564 — merged diff & reviews](https://github.com/flutter/flutter/pull/195564) |
| **Dart-Code / DTD lifecycle (merged):** asynchronous device and service events could outlive VS Code extension disposal and trigger errors. | Added lifecycle guards and regression coverage for shutdown/disposal races, worked through maintainer reviews, and landed the fix on **5 Nov 2026**. | [Dart-Code #6349 — merged code & review](https://github.com/Dart-Code/Dart-Code/pull/6349) |
| **Dart-Code / CI reliability (merged):** tests spawned real Dart/Flutter tools and sometimes contacted the network simply to verify command invocation and output. | Replaced tool spawns with deterministic stubs, confirmed output assertions and tests; one focused Flutter group went from ~24s to ~3s locally. Maintainer DanTup approved the changes. Merged **7 Nov 2026**. | [Dart-Code #6373 — merged code and review](https://github.com/Dart-Code/Dart-Code/pull/6373) |
| **Flutter Web scrolling semantics (human-approved; not merged):** after a scrollable list shrank, stale semantic DOM offsets made clicking the painted Row 4 activate Row 2. | Corrected stale offset handling and added regression checks. Reviewer `flutter-zl` independently verified the [before demo](https://flutter-demo-93-before.web.app) and [after demo](https://flutter-demo-93-after.web.app), then approved the PR. It is still open. | [Flutter #195578 — approval & diff](https://github.com/flutter/flutter/pull/195578) |

*Status snapshot: 7 November 2026. The scrolling fix #195578 is **approved but not merged**; the DTD lifecycle fix #6349 **is merged**. CI, draft status and human approval are not merge records. I distinguish shipped work, upstream merges, private client delivery and in-review submissions.*

**My workflow:** reproduce a real failure → write a focused regression → fix the smallest safe path → run tests and static checks → address technical review. This is also how I work on production Flutter apps and backend APIs.

[**Explore NEMESIS / Engineering →**](https://nemesisdevx.github.io/) · [Detailed case studies](https://nemesisdevx.github.io/work.html#case-studies)

## Shipped software

### [Tasbehati / تسبيحاتي](https://play.google.com/store/apps/details?id=com.tasbehati.ai.pr)

A **published Flutter Android application** for Quran reading, adhkar, tasbih, prayer times, and daily spiritual tools. Built and maintained with practical experience in production debugging, Firebase, mobile release engineering, and monetization.

**Production evidence:** [Open Tasbehati on Google Play](https://play.google.com/store/apps/details?id=com.tasbehati.ai.pr) · Android production release · Source is private.

| Engineering strengths | Real-world scope |
| :--- | :--- |
| **Mobile delivery** | Android app release and ongoing maintenance |
| **Debugging & reliability** | Crash fixes, regression analysis, and UI behavior |
| **Integrations** | Firebase, REST APIs, and mobile ads |
| **Testing** | Focused regressions, release checks, and device validation |

## Work currently under upstream review

**16 open external PRs, including Draft submissions, as of 7 November 2026.** This is a dated snapshot, not a claim of approval or merging. [Check the live GitHub PRs](https://github.com/pulls?q=is%3Apr+author%3ANemesisDevX+is%3Aopen).

| Upstream | Engineering change and review state | Evidence |
| :--- | :--- | :--- |
| **Flutter / Web accessibility** | Fixed stale semantic scrolling offsets; **approved** by `flutter-zl`, internal Google tests rerunning | [flutter/flutter #195578](https://github.com/flutter/flutter/pull/195578) |
| **Flutter / Sliver semantics** | Exclude pinned children pushed outside a group's visible region; awaiting human review | [flutter/flutter #196016](https://github.com/flutter/flutter/pull/196016) |
| **Flutter / Native assets** | Repair macOS `otool` architecture parsing for paths with parentheses; **Draft** | [flutter/flutter #196060](https://github.com/flutter/flutter/pull/196060) |
| **Flutter / Accessibility checks** | Detect unnamed link semantics nodes; **Draft**, awaiting design agreement | [flutter/flutter #196080](https://github.com/flutter/flutter/pull/196080) |
| **Dart-Code / DTD requests** | Settle pending calls and guard sends when sockets close; **Ready for Review**, CI green | [Dart-Code #6367](https://github.com/Dart-Code/Dart-Code/pull/6367) |
| **Dart-Code / DTD messages** | Log unobserved asynchronous message-handler failures; **Draft**, CI green | [Dart-Code #6372](https://github.com/Dart-Code/Dart-Code/pull/6372) |
| **Dart packages / pool** | Restore repeated pending-request timeouts; **approved** by `sigurdm` | [dart-lang/tools #2763](https://github.com/dart-lang/tools/pull/2763) |
| **Dart packages / pub_semver** | Safely subtract empty version constraints; awaiting human review | [dart-lang/tools #2797](https://github.com/dart-lang/tools/pull/2797) |
| **Dart packages / mime** | Correct Ogg, binary glTF and PostScript signatures; **Draft**, focused tests passing | [dart-lang/tools #2802](https://github.com/dart-lang/tools/pull/2802) |
| **Dart packages / unified_analytics** | Add fallback root-tool resolution to child-process analytics environments; **Draft**, bot feedback addressed | [dart-lang/tools #2806](https://github.com/dart-lang/tools/pull/2806) |
| **Dart packages / csslib strings** | Preserve escaped quote characters during CSS parsing and printing; **Draft** | [dart-lang/tools #2807](https://github.com/dart-lang/tools/pull/2807) |
| **Dart packages / csslib recovery** | Avoid losing stylesheet rules after malformed Media Queries; **Draft**, does not yet support MQ4 ranges | [dart-lang/tools #2808](https://github.com/dart-lang/tools/pull/2808) |
| **Flutter DevTools / Layout** | Prevent Network toolbar overflow on small screens; feedback addressed, follow-up review pending | [flutter/devtools #10057](https://github.com/flutter/devtools/pull/10057) |
| **Flutter DevTools / Build** | Prune unused engine assets in extension builds with regression tests; waiting on reviewers | [flutter/devtools #10063](https://github.com/flutter/devtools/pull/10063) |
| **Apple Pkl / Packaging** | Preserve Kotlin reflection while shading fat JARs; awaiting human review | [apple/pkl #1961](https://github.com/apple/pkl/pull/1961) |
| **React Native / Android Gradle** | Generate variant-specific PackageList classes; **CLA signed**, pending human review | [react/react-native #59739](https://github.com/react/react-native/pull/59739) |

## Selected engineering projects

| Project | Evidence and scope |
| :--- | :--- |
| **FamilyMove / family fitness (private client pilot)** | Flutter Android + Laravel backend, family accounts, push notifications, reporting and production-oriented QA; private client work, not a public release | 
| **[VoiceOps Controller](https://github.com/NemesisDevX/VoiceOps-Controller)** | Python / FastAPI infrastructure control, human confirmation for actions and regression testing |
| **[voxguard / PauseSignal](https://github.com/NemesisDevX/voxguard)** | Flutter voice-scam risk prototype with family alerts; **experimental, not a validated detector** · [Demo](https://nemesisdevx.github.io/voxguard/) |
| **[Zero-Day AI Auditor](https://github.com/NemesisDevX/Zero-Day-AI-Auditor)** | Experimental Solidity checks with local Anvil simulations; **no claim of discovered zero-days** |

## Toolkit

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

**Especially interested in:** Flutter internals, accessibility, editor integrations, automated tests, Python APIs, CI reliability, and authorized security research.

## Let's work together

**Available for:** paid remote Flutter / Dart development, Android engineering, developer tooling, testing, Python APIs, Laravel backends, and focused contract projects. Based in **Egypt**.

| Contact | Direct link |
| :--- | :--- |
| **Email** | [abdelrhmanmahrous386@gmail.com](mailto:abdelrhmanmahrous386@gmail.com) |
| **Phone** | [+20 10 6747 5499](tel:+201067475499) |
| **WhatsApp** | [Chat on WhatsApp](https://wa.me/201067475499) |
| **Telegram** | [Chat by phone number](https://t.me/+201067475499) |
| **LinkedIn** | [Professional profile](https://www.linkedin.com/in/abdellrhman-darweish-0b6144433/) |

<sub>Telegram's phone-based chat link depends on whether my account allows discovery by phone number. For a reliable first contact, please use email or WhatsApp.</sub>

<div align="center">
  <hr />
  <p><strong>Less noise. More code. More reproducible evidence.</strong></p>
  <p><a href="https://nemesisdevx.github.io/">NEMESIS / Engineering</a> · <a href="https://nemesisdevx.github.io/assets/Abdelrahman_Darwish_Engineering_CV_2026.pdf">Resume (PDF)</a> · <a href="https://nemesisdevx.github.io/portfolio.html">Detailed case studies</a> · <a href="mailto:abdelrhmanmahrous386@gmail.com">Email me</a> · <a href="https://wa.me/201067475499">WhatsApp</a></p>
</div>
