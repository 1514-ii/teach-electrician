# Learning State

Last updated: 2026-07-14

## Current Exam Goal

- 전기기사 실기 합격

## Current Level

- 별도 1문제 대화형 진단 5문제를 완료했다.
- 비공개 자료 기반은 준비됨: 기존 PDF 원문 7개, 검색 확보 PDF 11개, 사용자 추가 PDF 4개.
- 2024년 1회 1-15번 lesson 3개 작성 및 공개본 동기화 완료.

## Operating Mode

- HTML-first
- 하루 5문제
- 기출 중심
- GitHub Pages 공개 HTML로 회사/모바일 학습
- ChatGPT Markdown은 보조 설명과 복습 대화용

## Latest Lesson

- [2024년 1회 11-15번: 표·논리·단위 문제를 빠르게 분류하기](lessons/0003-2024-01-eleven-to-fifteen.html)

## Latest Reference

- [YouTube 강의자료 지도](reference/0002-youtube-study-map.html)
- [실기 이론 지도](reference/0001-core-theory-map.html)

## Interactive Diagnostic

- 기존 HTML lesson 진행과 분리해 한 번에 한 문제씩 진행한다.
- 답변 순서: 유형 추정 -> 주어진 조건 -> 공식/판단 근거 -> 풀이와 단위 -> 확신도.
- 1번 3상 전동기 선전류: 효율과 `sqrt(3)` 위치에서 막혔으나 힌트 후 `46.32 A`를 산출했다. 확신도 80%.
- 2번 변압기 용량: 수용률의 곱셈 방향과 종합역률 적용 범위를 힌트 후 바로잡았다. 최초 확신도 90%는 과신이었고, 계산은 생략하고 식만 확인했다.
- 3번 3상 3선식 전압강하: 힌트 후 `e = sqrt(3)IR`와 km 환산을 적용해 식을 세웠고, 결과는 약 `3.46 V`, `0.91%`로 확인했다. 확신도 90%.
- 4번 펌프용 전동기 출력: 처음 출제한 단순 효율 문제는 진단에서 제외하고, 공개 lesson 기반 자작 변형으로 교체했다. `P = QHK / (6.12η)`를 정확히 인출했고, 효율 소수 변환을 확인했다. 확신도 80%.
- 5번 XOR 논리: 처음 출제한 램프 효율 문제는 학습자 판단에 따라 진단에서 제외하고, XOR 진리표 문제로 교체했다. “같을 때 0, 다를 때 1”을 즉시 인출했다. 확신도 100%.
- 5문제 요약: 5문제 모두 최종 정답 흐름에 도달했다. 1~3번은 각 1회 힌트가 필요했고, 4~5번은 공식/판단 근거를 바로 인출했다. 반복 실수 후보는 효율의 위치와 소수 변환, `sqrt(3)` 계수, 단위 환산이다.
- 현재 관찰: 문제 유형과 조건 인식은 양호하고, 공식의 적용 방향과 조건 문구 해석에서 인출 오류가 발생한다. 힌트 후 회복은 빠르며, 확신도는 대체로 높게 잡는 편이다.
- 운영 조정: 식이 맞으면 산술 계산은 생략하고, 정답 설명보다 개념과 공식 인출을 우선한다. 다음 대화형 진단은 효율/역률/단위 환산을 섞은 짧은 회상 문제부터 시작한다.

## Source Status

- 공개 가능한 자료: YouTube 강의 링크 9개
- 비공개 원문 자료: Gmail 대용량 링크 PDF 4개를 `source-materials/gmail-2026-06-30-electrical-practical/`에 저장
- 추가 비공개 원문 자료: 학습자료2 PDF 3개를 `source-materials/gmail-2026-06-30-electrical-practical-2/`에 저장
- 공개 YouTube 강의자료 9개를 `RESOURCES.md`에 등록하고 `reference/0002-youtube-study-map.html`로 분류
- YouTube clean transcript 97개와 topic index를 ignored `source-materials/youtube-transcripts/`, `source-materials/youtube-analysis/`에 저장
- YouTube/웹 검색 관련 PDF 11개와 사용자 추가 PDF 4개, topic index를 ignored `source-materials/found-pdfs/`에 저장
- 다산E북/린치핀/전기치트키 PDF 후보는 자동 다운로드하지 않고 `source-materials/found-pdfs/README.md`에 상태만 기록
- 감리문제 PDF 2개는 해시가 같아 중복 1개만 `source-materials/found-pdfs/downloads/practical-supervision-2016-2021.pdf`로 보관
- Gmail 직접 첨부 PDF 5개는 커넥터 제한으로 수동 다운로드 필요
- PDF 원문, 유료교재 원문, 기출문제 원문 전체는 Git 커밋 금지

## Lesson Output Rules

- 작성본: `lessons/*.html`
- 공개본: `docs/lessons/*.html`
- 참고자료 작성본: `reference/*.html`
- 참고자료 공개본: `docs/reference/*.html`
- 공개 HTML에는 문제 요약, 풀이 흐름, 공식, 오답 포인트, 자작 변형문제만 포함
- 각 lesson에는 버튼형 퀴즈와 즉시 피드백 포함

## Next

- 별도 대화형 진단 5/5가 완료되었으므로, 다음에는 효율/역률/단위 환산을 섞은 짧은 회상 문제부터 시작한다.
- 직전 범위의 PLC 명령어 구조, XOR truth table, 램프 효율, 펌프 출력 공식을 짧게 회상한다.
- 다음 lesson은 `2024년 1회 16-18번 + 2024년 2회 1-2번`의 5문제 세트로 작성한다.
- 작성 전에는 ignored 원문에서 필요한 문제 축만 확인하고, 공개본에는 재작성한 요약과 자작 변형문제만 넣는다.
- 감리/단답/필기 배경 보강은 `source-materials/found-pdfs/analysis/topic-index.md`를 우선 사용한다.
- 문제축별 연결 강의는 `reference/0002-youtube-study-map.html`에서 1개만 고른다.
