# 김형준 (Heung Jun Kim)

신입 AI 엔지니어입니다. 기준을 먼저 세우고, LLM과 AI 코딩 에이전트가 낸 결과를 그 기준으로 검증합니다. 구현을 AI 코딩 에이전트에 맡긴 곳은 표에 괄호로 밝혔습니다.

사례 문서 4편은 [포트폴리오 저장소](https://github.com/khj1212k/portfolio)에 있습니다. [English](https://github.com/khj1212k/portfolio/blob/main/README.en.md)

| 프로젝트 | 한 일 | 결과와 확인할 자료 |
| --- | --- | --- |
| [Trip.com LLM 번역 파이프라인](https://github.com/khj1212k/portfolio/blob/main/projects/tripcom-llm-translation.md)<br>인턴, 2024.11 ~ 2025.02 | LLM 번역 도입을 사내 문서로 제안, 틀리면 여행자가 피해를 보는 필드부터 검수하는 기준과 프롬프트 틀 설계, 5개 LLM을 같은 입력으로 비교 | 관광지 9,755곳의 한국어 커버리지 72.3%에서 100%. 회사 자료라 코드는 비공개 |
| [LangGraph 뉴스레터 생성](https://github.com/khj1212k/portfolio/blob/main/projects/newsletter-langgraph.md)<br>5인 팀 팀장, 2026.01 ~ 2026.02, 이후 개인 후속 작업 | 생성과 평가를 LangGraph 노드로 분리, 2단계 군집, 배치 주기 설계. 팀 종료 뒤 fork에서 원문 대조 검사 추가(구현은 AI 코딩 에이전트) | 팀 종료 뒤 커밋 463개, 설계 결정 기록 19건, CI 테스트는 푸시마다 실행되고 2026-10-06 기준 최신 커밋은 통과. [코드와 tests/, docs/adr/](https://github.com/khj1212k/pro-recsys-finalproject-recsys-01) |
| [LG Aimers 9기 해커톤](https://github.com/khj1212k/portfolio/blob/main/projects/lg-aimers-agent-validation.md)<br>5인 팀, 2026.08 ~ 2026.09 | 로컬 검증 1위 조합이 제출에서 415점으로 떨어진 뒤, 검증을 실제 제출 조건에 맞춰 다시 세우고 통과한 버전만 제출(구현은 AI 코딩 에이전트) | 개인 탐색 트랙 783.78점에서 983.26점. 팀은 1,030팀 중 17위로, 34팀이 선발된 본선에 진출. [DACON 리더보드](https://dacon.io/competitions/official/236743/leaderboard) 17위 행 |
| [시각-언어 모델 행인 재식별 연구](https://github.com/khj1212k/portfolio/blob/main/projects/vlm-person-reid-thesis.md)<br>개인 연구, 2025.03 ~ 2025.05 | 7B 모델의 전체 미세조정과 PEFT 3종을 총 학습 시간을 맞춰 비교, 2단계 전이 설계 | 동일인 판별 정확도 97.05%(Market-1501). 제1저자 학술대회 논문 2편. [학습 스크립트 fork](https://github.com/khj1212k/lmms-finetune) 커밋 5개 |

[LinkedIn](https://www.linkedin.com/in/heung-jun-kim-46652031a)
