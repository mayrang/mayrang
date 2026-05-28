<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=mayrang&fontSize=60&fontAlignY=35&desc=Frontend%20Engineer%20%C2%B7%20Open%20Source%20Contributor&descSize=18&descAlignY=58" alt="header" />

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=600&color=3178C6&center=true&vCenter=true&width=520&lines=Frontend+Engineer;Contributing+to+Lexical;Author+of+formdraft;Open+Source+Enthusiast" alt="typing" />
  </a>

</div>

<div align="center">

  <p>
    I am a Frontend Engineer with a background in open-source contributions to rich-text editors and text-rendering libraries.<br/>
    Currently, I am seeking frontend developer positions.<br/>
    My long-term goal is to specialize in rich-text editor core development,<br/>
    contributing deeply to projects like Lexical.
  </p>

  <p>
    리치 텍스트 에디터와 텍스트 렌더링 라이브러리 오픈소스에 기여해 온 프론트엔드 엔지니어입니다.<br/>
    현재 프론트엔드 개발자 포지션을 찾고 있습니다.<br/>
    장기적으로는 리치 텍스트 에디터 코어 개발에 집중하여,<br/>
    Lexical과 같은 프로젝트에 깊이 기여하는 것을 목표로 합니다.
  </p>

</div>

<div align="center">

  <img src="https://img.shields.io/badge/Lexical-28_PRs_merged-3178C6?style=for-the-badge&logo=meta&logoColor=white" alt="Lexical contributions" />
  <img src="https://img.shields.io/badge/Pretext_%E2%98%85_47k-3_landed-FF6B35?style=for-the-badge" alt="Pretext contributions" />
  <a href="https://www.npmjs.com/package/formdraft"><img src="https://img.shields.io/badge/formdraft-v0.3.0_on_npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="formdraft on npm" /></a>
  <img src="https://img.shields.io/badge/Open_Source-Active_Contributor-2EA44F?style=for-the-badge&logo=github&logoColor=white" alt="OSS active" />

</div>

---

## Projects

### [formdraft](https://github.com/mayrang/formdraft) — React form auto-save library
`v0.3.0` · 5.8 KB brotli · zero runtime deps · 216 unit + 87 Playwright e2e (Chromium / Firefox / WebKit)

폼이 새로고침 / 오프라인 / 멀티탭 충돌에서 살아남게 만드는 React 라이브러리. 매번 프로젝트마다 다시 짜던 ~700줄짜리 자체 구현을 패키지로 묶음. React Hook Form / Formik / TanStack Form 어댑터 포함, `autoAdapter`로 localStorage → IndexedDB 자동 마이그레이션, `<ConflictDialog>` 멀티탭 충돌 머지 UI, `fieldsNeedingReentry`로 비번 reentry 알림까지.

- npm: [`formdraft`](https://www.npmjs.com/package/formdraft)
- `npm install formdraft`

---

## Open Source Contributions

### [facebook/lexical](https://github.com/facebook/lexical) — 28 merged (★23k)
Meta의 리치 텍스트 에디터 프레임워크. 코어 패키지(`lexical`, `lexical-list`, `lexical-rich-text`, `lexical-markdown`, `lexical-code-core`)와 playground 양쪽에 기여.

Highlights
- [#8519](https://github.com/facebook/lexical/pull/8519) **Breaking** · Generalize `DOMSlot` and add `DOMRenderExtension` override surface — 5 packages, opens up `TextNode` DOM scoping & external HTML rendering hooks
- [#8482](https://github.com/facebook/lexical/pull/8482) **Perf** · Children fast path with suffix-incremental cache update in `$reconcileChildren` — O(N) → O(K) for typing-at-end
- [#8481](https://github.com/facebook/lexical/pull/8481) **Perf** · Adopt GenMap copy-on-write for `NodeMap` and reconciler `keyToDOMMap`
- [#8542](https://github.com/facebook/lexical/pull/8542) Detect infinite recursion in update listeners — per-editor cascade counter prevents the documented "watch out for infinite loops" footgun from hanging the browser
- [#8558](https://github.com/facebook/lexical/pull/8558) Bug Fix · Cursor stuck before leading inline `DecoratorNode` — cross-package selection-engine fix (lexical / rich-text / code-core)
- [#8505](https://github.com/facebook/lexical/pull/8505) Refactor · Centralize replace-area selection mapping + bulk splice across `lexical` / `list` / `selection` / `link`
- [#8395](https://github.com/facebook/lexical/pull/8395) Add `$convertSelectionToMarkdownString` public API

### [chenglou/pretext](https://github.com/chenglou/pretext) — 3 contributions landed (★48k)
Fast, accurate text measurement & layout 라이브러리. 메인테이너가 PR을 close하고 본인 커밋에 공동작업자로 합치는 방식이라, 기여는 PR이 아닌 커밋 SHA로 들어감.

- [`1a8b2ae`](https://github.com/chenglou/pretext/commit/1a8b2ae) feat: add `letterSpacing` support
- [`d9f2dff`](https://github.com/chenglou/pretext/commit/d9f2dff) fix: keep CJK opening brackets with annotations
- [`c28eecb`](https://github.com/chenglou/pretext/commit/c28eecb) fix: align line walkers and Hangul jamo breaks

### Other
- [vitest-dev/vitest #10188](https://github.com/vitest-dev/vitest/pull/10188) — `fix(snapshot): treat empty string as valid snapshot`
- [vitest-dev/ivya #17](https://github.com/vitest-dev/ivya/pull/17) — `fix: support empty template in parseAriaTemplate`
- [recharts/recharts #7273](https://github.com/recharts/recharts/pull/7273) — `fix: use originalDataIndex for tooltip dispatch in Bar`

---

<div align="center">
  <h2>Contact</h2>
  <p>
    <a href="mailto:pkss0626@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/%EA%B1%B4%EC%83%81-%EB%B0%95-396933303"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
    <a href="https://velog.io/@mayrang/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white"></a>
  </p>
</div>

<div align="center">
  <h2>Stats</h2>
  <p>
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mayrang&theme=tokyonight" height="170px"/>
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=mayrang&theme=tokyonight" height="170px"/>
  </p>
</div>
