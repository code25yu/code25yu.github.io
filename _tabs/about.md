---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

<style>
.lang-tabs input[type="radio"] {
  position: absolute;
  opacity: 0;
  pointer-events: none;
}
.lang-tab-buttons {
  display: flex;
  gap: 0.5rem;
  margin-bottom: 1.2rem;
  border-bottom: 1px solid rgba(127, 127, 127, 0.3);
}
.lang-tab-buttons label {
  cursor: pointer;
  padding: 0.4rem 0.9rem;
  border-radius: 0.4rem 0.4rem 0 0;
  font-weight: 600;
  opacity: 0.6;
  border-bottom: 2px solid transparent;
  transition: opacity 0.15s ease, border-color 0.15s ease;
}
.lang-tab-buttons label:hover {
  opacity: 1;
}
.lang-content {
  display: none;
}
#lang-ko:checked ~ .lang-tab-buttons label[for="lang-ko"],
#lang-en:checked ~ .lang-tab-buttons label[for="lang-en"],
#lang-ja:checked ~ .lang-tab-buttons label[for="lang-ja"] {
  opacity: 1;
  border-bottom-color: currentColor;
}
#lang-ko:checked ~ #content-ko,
#lang-en:checked ~ #content-en,
#lang-ja:checked ~ #content-ja {
  display: block;
}
</style>

<div class="lang-tabs" markdown="0">
  <input type="radio" name="lang" id="lang-ja" checked>
  <input type="radio" name="lang" id="lang-en">
  <input type="radio" name="lang" id="lang-ko">

  <div class="lang-tab-buttons">
    <label for="lang-ja">日本語</label>
    <label for="lang-en">English</label>
    <label for="lang-ko">한국어</label>

  </div>

<div class="lang-content" id="content-ja" markdown="1">

> テクノロジーと人々の暮らしをつなぐ価値を創り出すエンジニアを目指しています。

## プロフィール

- **氏名**: Shin Yubin
- **メール**: [code25yu@gmail.com](mailto:code25yu@gmail.com)

## 学歴

- **2026年 – 現在** `42 Tokyo` — 在学中
- **2025年** `淑明女子大学校` — 韓国語文学専攻（経営学副専攻）
- **2025年** `42 Seoul` — Common Core課程修了
- **2022年** `ITWILL` — ビッグデータ・機械学習研修課程修了

## 資格

- `JLPT N1`（日本語能力試験）
- `TOEIC L&R` 820点
- `情報処理技師`（韓国国家技術資格、日本の応用情報技術者試験に相当）
- `コンピュータ活用能力1級`（Excel・Access上級）

## スキル

- **Languages**: `C` `C++` `Shell(Bash)` `TypeScript`　`Python`　
- **Frameworks**: `Fastify`
- **Databases**: `SQLite`
- **Tools**: `Git` `Linux` `Docker` `Makefile` `VSCode`

## リンク

- [GitHubプロフィール](https://github.com/code25yu?tab=repositories) — ポートフォリオプロジェクトとアルゴリズム練習用リポジトリを中心とした個人GitHub
- [42 Project](https://github.com/orgs/code25yu-42project/repositories) — 42のカリキュラムで取り組んだプロジェクトのリポジトリ集
- [ITWILL Project](https://github.com/iw35) — ITWILLの研修課程で行った機械学習・データ関連プロジェクト

</div>

<div class="lang-content" id="content-en" markdown="1">

> I aspire to become an engineer who creates meaningful intersections between technology and people's lives.

## Profile

- **Name**: Yubin Shin
- **Mail**: [code25yu@gmail.com](mailto:code25yu@gmail.com)

## Education

- **2026 – Present** `42 Tokyo` — Currently enrolled
- **2025** `Sookmyung Women's University` — B.A. in Korean Literature (Double Major in Business Administration)
- **2025** `42 Seoul` — Common Core completed
- **2022** `ITWILL` — Big Data & Machine Learning Training Program completed

## Certifications

- `JLPT N1` (Japanese Language Proficiency Test)
- `TOEIC L&R` 820
- `Engineer Information Processing` (Korea National Technical Qualification, comparable to Japan's Applied Information Technology Engineer Exam)
- `Computer Application Specialist Level 1` (Advanced Excel & Access)

## Skills

- **Languages**: `C` `C++` `Shell(Bash)` `TypeScript`　`Python`　
- **Frameworks**: `Fastify`
- **Databases**: `SQLite`
- **Tools**: `Git` `Linux` `Docker` `Makefile` `VSCode`

## Links

- [GitHub Profile](https://github.com/code25yu?tab=repositories) — Personal GitHub profile with pinned portfolio projects, and repositories mainly focused on algorithm practice.
- [42 Project](https://github.com/orgs/code25yu-42project/repositories) — Repository collection for projects completed during the 42 curriculum
- [ITWILL Project](https://github.com/iw35) — Machine learning and data-related projects developed during the ITWILL curriculum

</div>

<div class="lang-content" id="content-ko" markdown="1">

> 기술과 사람들의 삶이 교차하는 지점을 만드는 엔지니어를 목표로 하고 있습니다.

## Profile

- **Name**: Shin Yubin
- **Mail**: [code25yu@gmail.com](mailto:code25yu@gmail.com)

## Education

- **2026 – Present** `42 Tokyo` — 재학 중
- **2025** `Sookmyung Women's University` — 국어국문학 전공 (경영학 복수전공)
- **2025** `42 Seoul` — Common Core 과정 수료
- **2022** `ITWILL` — 빅데이터 & 머신러닝 교육과정 수료

## Certifications

- `JLPT N1` (일본어능력시험)
- `TOEIC L&R` 820
- `정보처리기사` (한국 국가기술자격, 일본의 応用情報技術者試験에 준하는 자격)
- `컴퓨터활용능력 1급` (Excel & Access)

## Skills

- **Languages**: `C` `C++` `Shell(Bash)` `TypeScript`　`Python`　
- **Frameworks**: `Fastify`
- **Databases**: `SQLite`
- **Tools**: `Git` `Linux` `Docker` `Makefile` `VSCode`

## Links

- [GitHub Profile](https://github.com/code25yu?tab=repositories) — 개인 GitHub, 포트폴리오 프로젝트 및 알고리즘 연습 저장소
- [42 Project](https://github.com/orgs/code25yu-42project/repositories) — 42 커리큘럼 진행 중 완료한 프로젝트 모음
- [ITWILL Project](https://github.com/iw35) — ITWILL 교육과정에서 진행한 머신러닝/데이터 관련 프로젝트

</div>

</div>
