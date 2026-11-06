<div align="center">
  <img src="./assets/nemesis-banner.svg" width="100%" alt="NemesisDevX — Flutter, Dart, developer tooling and systems engineering" />

  <h2>Abdelrahman Darwish <sub>· NemesisDevX</sub></h2>
  <p><strong>Flutter &amp; Dart · VS Code tooling · Android · Backend APIs · Regression Testing</strong></p>
  <p>16 months of hands-on Flutter/Dart experience since July 2025 · Published Android app · Private client pilot</p>
  <p>Reproduce the bug. Understand the cause. Ship the fix. Prove it works.</p>
  <p><strong>7 merged engineering pull requests</strong> across Flutter, Apple-maintained Pkl tooling and Dart-Code · Available for paid remote and contract engineering.</p>

  <p>
    <a href="https://github.com/NemesisDevX/NemesisDevX#merged-upstream"><img src="https://img.shields.io/badge/07-MERGED%20ENGINEERING%20PRs-cb254a?style=flat-square" alt="7 merged engineering upstream pull requests" /></a>
    <a href="https://play.google.com/store/apps/details?id=com.tasbehati.ai.pr"><img src="https://img.shields.io/badge/ANDROID-APP%20SHIPPED-237e68?style=flat-square" alt="Android app shipped" /></a>
    <a href="https://github.com/NemesisDevX?tab=repositories"><img src="https://img.shields.io/badge/FOCUS-TESTED%20ENGINEERING-454c62?style=flat-square" alt="Tested engineering" /></a>
  </p>
  <p>
    <a href="https://nemesisdevx.github.io/portfolio.html">Engineering portfolio</a> &nbsp; · &nbsp;
    <a href="https://github.com/NemesisDevX?tab=repositories">Repositories</a> &nbsp; · &nbsp;
    <a href="https://www.linkedin.com/in/abdellrhman-darweish-0b6144433/">LinkedIn</a>
  </p>
  <p>
    <a href="mailto:abdelrhmanmahrous386@gmail.com"><img alt="Email" src="https://img.shields.io/badge/EMAIL-Contact%20me-8c2c47?style=flat-square&logo=gmail&logoColor=white" /></a>
    <a href="https://wa.me/201067475499"><img alt="WhatsApp" src="https://img.shields.io/badge/WHATSAPP-Message%20me-1d9c69?style=flat-square&logo=whatsapp&logoColor=white" /></a>
    <a href="https://t.me/+201067475499"><img alt="Telegram by phone" src="https://img.shields.io/badge/TELEGRAM-Message%20me-2685af?style=flat-square&logo=telegram&logoColor=white" /></a>
    <a href="tel:+201067475499"><img alt="Phone" src="https://img.shields.io/badge/PHONE-%2B20%2010%206747%205499-343a4a?style=flat-square&logo=googlevoice&logoColor=white" /></a>
  </p>
  <p><sub>Based in Egypt &middot; Available for paid remote roles, contract work and focused engineering projects.</sub></p>
</div>

---

## Merged upstream

**7 verified merged upstream engineering PRs as of 7 November 2026.** Real bug fixes and regression tests accepted after upstream review. Every link points to the corresponding public code, discussion, and merge record; contributions do not imply employment by the projects or their parent organizations.

| Contribution | Engineering impact | Merged upstream |
| :--- | :--- | :--- |
| **Flutter Core / Web Engine** | Fixed initial accessibility value/range synchronization when a previously disabled slider becomes enabled; reviewer-validated regression coverage | [flutter/flutter #195564](https://github.com/flutter/flutter/pull/195564) |
| **Dart-Code / VS Code** | Fixed hidden ancestor directories breaking Dart test filtering and `pubspec.yaml` handling | [Dart-Code #6301](https://github.com/Dart-Code/Dart-Code/pull/6301) |
| **Dart-Code / SDK discovery** | Added SDK search-precedence tests, including Flutter, Fuchsia, PATH, and Bazel fallback; removed obsolete `DART_PATH_OVERRIDE` handling | [Dart-Code #6337](https://github.com/Dart-Code/Dart-Code/pull/6337) |
| **Apple / pkl-neovim** | Corrected nested Pkl language-server settings and added a headless Neovim regression harness | [apple/pkl-neovim #75](https://github.com/apple/pkl-neovim/pull/75) |
| **Dart-Code / Package testing** | Expanded automated coverage for package commands and `pubspec.yaml` update guards, with maintainer-requested test isolation | [Dart-Code #6332](https://github.com/Dart-Code/Dart-Code/pull/6332) |
| **Dart-Code / Project creation** | Added 12 tests for `dart.createProject`, SDK configuration, cancellation and error paths | [Dart-Code #6324](https://github.com/Dart-Code/Dart-Code/pull/6324) |
| **Dart-Code / DTD lifecycle** | Fixed disposal races, post-`await` continuations and late device/service events; regression tests and maintainer-requested cleanup | [Dart-Code #6349](https://github.com/Dart-Code/Dart-Code/pull/6349) |

<sub>These are upstream code and test contributions, not employment or affiliation with Flutter, Google, Apple or Microsoft. AI assistance was disclosed where applicable, and the links show independent review and merge evidence.</sub>

**Additional community contribution:** [CALLE-AI #600](https://github.com/CALLE-AI/awesome-phone-call-agents/pull/600) was merged on 14 September 2026. It is a community-directory submission, **not counted** in the seven engineering PRs above.

<p><a href="https://nemesisdevx.github.io/portfolio.html"><strong>↗ Explore verified engineering case studies</strong></a> &nbsp; · &nbsp; <a href="mailto:abdelrhmanmahrous386@gmail.com?subject=Remote%20engineering%20opportunity">Discuss a paid remote role or contract</a></p>

## Evidence-driven engineering: three case studies

| What broke | Fix & validation | Public proof |
| :--- | :--- | :--- |
| **Flutter Web accessibility (merged):** enabling a previously disabled slider could leave incorrect initial screen-reader value/range attributes. | Corrected the Web semantics initialization path, added regression coverage, and incorporated reviewer feedback. Merged **4 Nov 2026**. | [Flutter #195564 — merged diff & reviews](https://github.com/flutter/flutter/pull/195564) |
| **Flutter Web scrolling semantics (human-approved; not merged):** after a scrollable list shrank, stale semantic DOM offsets made clicking the painted Row 4 activate Row 2. | Corrected stale offset handling and added regression checks. Reviewer `flutter-zl` independently verified the [before demo](https://flutter-demo-93-before.web.app) and [after demo](https://flutter-demo-93-after.web.app), then approved the PR. It is still open. | [Flutter #195578 — approval & diff](https://github.com/flutter/flutter/pull/195578) |
| **Dart-Code DTD shutdown (merged):** in-flight device events and service handlers could outlive extension disposal, causing late sends or unhandled rejections. | Tightened disposal ordering, subscription cleanup and post-`await` guards; validated with focused regression suites and addressed maintainer feedback. **Merged 5 Nov 2026.** | [Dart-Code #6349 — merged code and review](https://github.com/Dart-Code/Dart-Code/pull/6349) |

*Snapshot: 7 November 2026. Flutter scrolling PR #195578 is human-approved but still open; Dart-Code #6349 was merged on 5 November. CI success, reviewer approval and a merge are distinct milestones.*

**My workflow:** reproduce a real failure → write a focused regression → fix the smallest safe path → run tests and static checks → address technical review. This is also how I work on production Flutter apps and backend APIs.

[**Explore the detailed case studies on my portfolio →**](https://nemesisdevx.github.io/portfolio.html#proof)

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

**13 open external engineering PRs as of 7 November 2026**, including drafts. These are proposals and patches under review, **not** merged work. Always check the linked PR for current status.

| Upstream project | Scope and verified status | PR |
| :--- | :--- | :--- |
| **Flutter Core / Web** | Accessible hit testing after list shrink · **human-approved**, Google testing underway | [#195578](https://github.com/flutter/flutter/pull/195578) |
| **Flutter Core / Framework** | Remove out-of-view pinned slivers from semantics · waiting for human review/Google tests | [#196016](https://github.com/flutter/flutter/pull/196016) |
| **Flutter Core / Tooling** | Otool parser handling of paths containing parentheses · **Draft** | [#196060](https://github.com/flutter/flutter/pull/196060) |
| **Flutter Core / Accessibility** | Validate link accessible names · **Draft**, pending proposal/design decision | [#196080](https://github.com/flutter/flutter/pull/196080) |
| **Dart-Code / DTD** | Reject pending calls on socket closure and protect async open handler · **Ready for Review**, CI green | [#6367](https://github.com/Dart-Code/Dart-Code/pull/6367) |
| **Dart-Code / DTD** | Log async message-handler failures rather than leaving unhandled rejections · **Draft**, CI green | [#6372](https://github.com/Dart-Code/Dart-Code/pull/6372) |
| **dart-lang/tools / pool** | Restore repeated pending-request timeouts · **human-approved**, awaiting merge | [#2763](https://github.com/dart-lang/tools/pull/2763) |
| **dart-lang/tools / pub_semver** | Handle empty constraints in `VersionUnion.difference` · under review | [#2797](https://github.com/dart-lang/tools/pull/2797) |
| **dart-lang/tools / mime** | Correct Ogg, glTF and PostScript magic bytes · **Draft**, local 105/105 tests | [#2802](https://github.com/dart-lang/tools/pull/2802) |
| **Flutter DevTools / UI** | Fix Network toolbar and footer overflow on narrow screens · reviewer feedback addressed | [#10057](https://github.com/flutter/devtools/pull/10057) |
| **Flutter DevTools / Build** | Prune unnecessary extension web engine assets · awaiting review | [#10063](https://github.com/flutter/devtools/pull/10063) |
| **Apple / Pkl** | Preserve Kotlin reflection in shaded fat JARs · open | [#1961](https://github.com/apple/pkl/pull/1961) |
| **React Native / Android** | Variant-aware autolinking PackageList generation · open | [#59739](https://github.com/facebook/react-native/pull/59739) |

<sub>These are time-stamped snapshots, not automatically updated badges. The PR links are the authoritative source for subsequent review or merge changes.</sub>

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
  <p><a href="https://nemesisdevx.github.io/portfolio.html">Portfolio & case studies</a> · <a href="mailto:abdelrhmanmahrous386@gmail.com">Email me</a> · <a href="https://wa.me/201067475499">WhatsApp</a></p>
</div>
