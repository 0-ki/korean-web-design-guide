# 당근 SEED를 한국어 제품 설계에 쓰는 방법

한국어 화면을 설계할 때 먼저 현재 제품의 사용자 과제와 브랜드를 확인하고, SEED에서 그 과제에 해당하는 지침을 고른다. 참고한 문서와 실제 화면에서 채택한 결정을 함께 남긴다. [당근 SEED](https://seed-design.io/)

| 지금 막힌 결정 | 열어 볼 문서 | 실제 화면에서 비교할 것 |
|---|---|---|
| 제목·본문·버튼이 비슷한 무게로 보인다 | [Typography](https://seed-design.io/foundations/typography) | 제목과 본문의 크기·행간·굵기를 역할 단위로 정한다. 한글 제목 두 줄, 숫자와 영문이 섞인 버튼, 긴 설명을 넣어 실제 폰트와 읽는 순서를 본다. |
| 문장이 딱딱하거나 다음 행동이 모호하다 | [Foundations의 Voice and Tone·Writing·Feedback](https://seed-design.io/foundations) | 가입, 실패, 복구 상황에 각각 맞는 문장을 작성한다. 예를 들어 이름을 입력하지 않은 폼에서는 어느 항목을 채우면 진행할 수 있는지 입력란 가까이에서 알려 준다. |
| 버튼·입력란·알림이 화면마다 다르다 | [Components의 Action Button·Field·Snackbar](https://seed-design.io/components) | 기존 컴포넌트에 주요 행동, 도움말, 오류, 처리 중 상태를 대응시킨다. 짧은 알림을 놓쳐도 사용자가 작업 결과를 확인할 수 있는지 살핀다. |
| 모바일에서 기다리는 이유가 불명확하거나 하단 버튼이 가려진다 | [Patterns의 Loading·Safe Area](https://seed-design.io/patterns) | 무엇을 기다리는지와 이미 조작 가능한 영역을 구분한다. 좁은 폭에서 하단 버튼을 누르고, 가상 키보드를 열고 닫은 뒤 원래 위치로 돌아오는지 확인한다. |
| React에서 직접 채택할 부품이 필요하다 | [React 라이브러리](https://seed-design.io/react) | 디자인 스펙에서 선택한 부품을 React API와 대조한다. 기존 시스템이 있는 프로젝트에서는 토큰·동작을 먼저 매핑하고 필요한 범위의 구현을 선택한다. |

## Codex와 Claude에서 필요한 문서 찾기

- **링크만 받은 경우** 공식 [llms.txt](https://seed-design.io/llms.txt)에서 Foundations, Components, Patterns 중 필요한 색인을 따라 해당 문서 한두 개를 읽는다. 디자인 스펙과 React 구현 API를 따로 찾을 수 있다.
- **반복해서 문서를 조회할 때** [Docs MCP](https://seed-design.io/ai-integration/docs-mcp)를, **SEED로 만든 Figma 시안을 구현할 때** [Figma MCP](https://seed-design.io/ai-integration/figma-mcp)를 참고한다.
- **이미 SEED를 쓰는 저장소를 검토할 때** 공식 [Doctor 스킬](https://seed-design.io/ai-integration/skill/doctor)로 설정·패키지 호환성·토큰·컴포넌트 사용을 읽기 전용으로 진단할 수 있다.

**지시 예시**　“당근 SEED의 Field, Action Button, Writing을 참고해 가입 폼을 개선해 줘. 우리 제품의 기존 색과 어투를 쓰고, 한국어 도움말·오류·제출 중 상태를 모바일에서 확인해 줘.”
