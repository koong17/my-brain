# suah-brain

수아(koong17)의 뇌. 에이전트는 이 폴더를 읽고 수아처럼 판단하고 일한다.

## 나는 누구인가 (3줄 요약)

<!-- 채울 것: 역할 + 현재 집중하는 일 + 일하는 방식 한 줄. 예시:
- 백엔드 엔지니어, OO 시스템 담당
- 지금은 X 프로젝트에 집중
- 근거 없는 추측 싫어함, 코드로 검증하고 말하기
-->

## 사용법

1. 판단이 필요하면 `identity/principles.md` 먼저 읽기
2. 시스템/도메인 사실은 `knowledge/`에서 찾기
3. 절차가 있는 작업(리뷰, 티켓)은 `workflows/` 따르기
4. 새로 배운 것은 `inbox.md`에 적기 — 분류는 나중에

## 인덱스

| 경로 | 내용 |
|------|------|
| `identity/profile.md` | 역할, 책임, 목표 |
| `identity/principles.md` | 기술 판단 기준 — 리뷰에서 막는 것, 아키텍처 취향 |
| `identity/style.md` | 코드 스타일, 커뮤니케이션 톤 |
| `knowledge/systems/` | 담당 시스템별 구조·주의점 (1시스템 1파일) |
| `knowledge/team.md` | 팀 구조, 사람별 컨텍스트 |
| `knowledge/glossary.md` | 사내 용어 |
| `workflows/` | 리뷰·티켓·루틴 절차 |
| `projects/` | 진행 중 프로젝트 컨텍스트 (1프로젝트 1폴더) |
| `decisions/` | 결정 기록 — "왜 그렇게 했나" |
| `inbox.md` | 미분류 메모 |
| `.agent/skills/` | 에이전트 공용 스킬 |
| `.agent/agents/` | 에이전트 공용 서브에이전트 정의 |

## 규칙

- 이 폴더의 글은 짧고 살아있게. 죽은 위키 금지.
- 수아의 교정/피드백 받으면 해당 파일에 즉시 반영.
- 에이전트 공용 리소스는 `.agent/`에만 작성. `.claude/`는 symlink + Claude 전용(hook 등)만.
