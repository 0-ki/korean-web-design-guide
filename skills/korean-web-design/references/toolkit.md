# 용도별 자료와 도구

도구는 막힌 결정에 맞춰 선택한다. 제품이 이미 가진 디자인 시스템과 CSS를 먼저 확인한다.

| 결정 | 후보 | 사용법 |
|---|---|---|
| 한국어 제품 UI의 위계·문구·상태 | [당근 SEED 활용 가이드](seed-design.md) | Foundations에서 역할을 정하고 Components와 Patterns에서 해당 동작을 확인한다. 에이전트는 공식 문서 색인으로 바로 들어갈 수 있다. |
| 랜딩의 사진·구도·타이포 | [Muzli](https://muz.li/) · [Lapa Ninja](https://www.lapa.ninja/) · [브런치](https://brunch.co.kr/) · [29CM](https://www.29cm.co.kr/) | 해외 사례에서 첫 화면 구도를 골랐다면 국내 콘텐츠에 실제 길이의 제목을 넣어 사진 비중과 정보 위계를 다시 잡는다. |
| 가입·입력·실패·복귀 동선 | [Mobbin](https://mobbin.com/) · [Mobbin MCP](https://mobbin.com/mcp) | 목표가 비슷한 흐름의 앞뒤 화면을 살핀다. 사례 검색을 자주 위임할 때 MCP의 제공 플랜을 확인한다. |
| CSS 패턴과 브라우저 호환성 | [Google Modern Web Guidance](https://github.com/GoogleChrome/modern-web-guidance) | 구현 직전 한 가지 문제로 검색한 뒤 해당 가이드를 읽는다. 예를 들어 CLI에서 `npx -y modern-web-guidance@latest search "wrap text lines"`를 실행하고 결과의 ID로 retrieve한다. 한국어 조판은 KLREQ와 대조한다. |
| React UI 구현 | [Tailwind CSS](https://tailwindcss.com/docs/theme) · [shadcn/ui MCP](https://ui.shadcn.com/docs/mcp) · [Radix Primitives](https://www.radix-ui.com/primitives/docs/overview/introduction) | 기존 CSS에서 구도를 해결할 수 있으면 그대로 쓴다. 새 React 서비스는 Tailwind 테마와 필요한 shadcn 컴포넌트부터, 고유 외형에 복잡한 키보드 동작이 필요한 경우에는 Radix부터 비교한다. |
| 시안 리뷰·디자인 인계 | [Impeccable](https://github.com/pbakaus/impeccable) · [Figma MCP](https://developers.figma.com/docs/figma-mcp-server/) | 실제 시안의 위계·밀도·여백을 비평하거나 이미 선택된 Figma 프레임을 전달할 때 쓴다. |
| 동작과 시각 검증 | [Playwright](https://playwright.dev/) · [Playwright MCP](https://github.com/microsoft/playwright-mcp) · [WAI](https://www.w3.org/WAI/tutorials/) | 실제 버튼 이름으로 주요 과제를 수행하고, 전후 스크린샷에서 사진 잘림·포커스·줄바꿈을 확인한다. |

## 배워서 바로 써 볼 자료

- 같은 화면에 간격·글꼴·강조를 하나씩 더하고 무엇이 읽기를 바꾸는지 확인한다. [Web Design in 4 Minutes](https://jgthms.com/web-design-in-4-minutes/)
- 제목·설명·버튼의 시선 순위를 바꾸는 연습에 사용한다. [Steve Schoger의 UI 디자인 발표](https://www.youtube.com/watch?v=Z79rrryI0C4) · [Refactoring UI](https://refactoringui.com/)
- 화면을 줄일 때 실제 문구와 조작이 먼저 깨지는 지점을 찾는다. [Kevin Powell의 반응형 웹 설계](https://www.youtube.com/watch?v=x4u1yp3Msao)

## 새로운 후보를 조사할 때

GitHub Trending은 조회한 날짜·언어·등장일과 누적 별을 구분해 기록한다. Hacker News는 기간·검색어·점수·댓글·원문을 함께 남긴다. 같은 한국어 콘텐츠와 사용자 과제로 현재 방식과 후보를 비교한 뒤 도입한다. [GitHub Trending](https://github.com/trending) · [일별 보관본](https://github.com/antonkomarev/github-trending-archive) · [HN 검색 API](https://hn.algolia.com/api)
