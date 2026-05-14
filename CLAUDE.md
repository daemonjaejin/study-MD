# CLAUDE.md - 공통 규칙

## 프로젝트 개요

- 이 저장소는 Claude Code 역할별 학습 및 히스토리 관리용입니다
- GitHub에 올려두고 새 현장 투입시 git clone으로 동일 환경 세팅

## 역할별 문서 위치

| 역할       | 기본 규칙                    | 히스토리                 |
| ---------- | ---------------------------- | ------------------------ |
| 프론트엔드 | @docs/frontend/frontend.md   | @docs/frontend/history/  |
| 백엔드     | @docs/backend/backend.md     | @docs/backend/history/   |
| DBA        | @docs/dba/dba.md             | @docs/dba/history/       |
| 아키텍처   | @docs/architect/architect.md | @docs/architect/history/ |
| 디자이너   | @docs/designer/designer.md   | @docs/designer/history/  |
| 퍼블리셔   | @docs/publisher/publisher.md | @docs/publisher/history/ |
| 기획자     | @docs/planner/planner.md     | @docs/planner/history/   |
| TA         | @docs/ta/ta.md               | @docs/ta/history/        |
| PL         | @docs/pl/pl.md               | @docs/pl/history/        |
| 공통개발팀 | @docs/common/common.md       | @docs/common/history/    |

## 히스토리 관리 규칙

- 파일명 형식: YYYY-MM-DD-AM.md 또는 YYYY-MM-DD-PM.md
- 3일치 히스토리가 쌓이면 아래 명령어로 요약 실행
- 요약 후 원본 파일은 history/archive/ 로 이동

## 히스토리 요약 명령어

작업할 역할의 히스토리를 요약할 때 아래처럼 호출
@docs/developer/developer.md @docs/developer/history/
최근 3일치 히스토리를 요약해서 developer.md에 반영하고
원본 파일은 archive로 이동해줘

## 공통 작업 규칙

- 모든 대화는 한국어로 진행
- 코드 설명시 파일명을 항상 명시할 것
- 하나씩 단계별로 진행하고 질의응답 후 다음 단계 진행
- 현업에서 사용하는 수준의 코드로 작성
