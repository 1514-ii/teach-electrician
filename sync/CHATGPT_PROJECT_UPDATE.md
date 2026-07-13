# ChatGPT Project Update

Last updated: 2026-07-14

## Mission

전기기사 실기 합격을 목표로, 기출 중심 하루 5문제 HTML lesson을 만든다.

회사/모바일 학습은 GitHub Pages에 공개 가능한 HTML만 올려서 사용한다.

## Current State

- 비공개 PDF 원문 7개를 `source-materials/`에 보관 중이다.
- 첫 reference: `reference/0001-core-theory-map.html`
- 공개본: `docs/reference/0001-core-theory-map.html`
- 첫 lesson: `lessons/0001-2024-01-first-five.html`
- 공개 lesson: `docs/lessons/0001-2024-01-first-five.html`
- 두 번째 lesson: `lessons/0002-2024-01-six-to-ten.html`
- 공개 lesson: `docs/lessons/0002-2024-01-six-to-ten.html`
- 세 번째 lesson: `lessons/0003-2024-01-eleven-to-fifteen.html`
- 공개 lesson: `docs/lessons/0003-2024-01-eleven-to-fifteen.html`
- YouTube 강의자료 9개 등록: `RESOURCES.md`
- YouTube reference: `reference/0002-youtube-study-map.html`
- 공개 YouTube reference: `docs/reference/0002-youtube-study-map.html`
- YouTube transcript private cache: 97 clean transcripts under ignored `source-materials/youtube-transcripts/`
- YouTube topic index: `source-materials/youtube-analysis/topic-index.md`
- YouTube/PDF related private cache: 15 downloaded PDFs under ignored `source-materials/found-pdfs/downloads/`
- PDF topic index: `source-materials/found-pdfs/analysis/topic-index.md`
- PDF source/candidate status: `source-materials/found-pdfs/README.md`
- User-added PDFs on 2026-07-03: supervision problems, Linchpin theory cheatkey, 27 practical-written theory questions, short-answer notes with answers
- 학습 재개 준비 완료: 다음 5문제 범위는 2024년 1회 16-18번 + 2024년 2회 1-2번
- 별도 1문제 대화형 진단은 5문제 중 2문제 완료, 3번째 문제 답변 대기 중

## How To Use This On Mobile

Ask ChatGPT for one short lesson or review prompt at a time. Keep source materials out of chat unless they are safe to share.

Suggested prompt:

```text
전기기사 실기 합격 목표로 teach-lite 방식으로 도와줘.
하루 5문제 기준으로, 문제 원문은 복사하지 말고
문제 요약, 풀이 흐름, 공식, 오답 포인트, 자작 변형문제로 수업을 만들어줘.
```

학습 재개용 프롬프트:

```text
전기기사 실기 학습을 이어가자.
직전 레슨은 2024년 1회 11-15번이며, 다음 범위는
2024년 1회 16-18번과 2024년 2회 1-2번이다.
문제 원문을 복사하지 말고, 공개 가능한 HTML lesson 기준으로
문제 요약, 풀이 흐름, 공식, 오답 포인트, 자작 변형문제와 즉시 피드백 퀴즈를 만들어줘.
```

Codex Cloud 대화형 학습 재개용 프롬프트:

```text
이 저장소의 AGENTS.md, MISSION.md, LEARNING_STATE.md, NOTES.md,
current_status.md, sync/CHATGPT_PROJECT_UPDATE.md를 먼저 읽어줘.

기존 HTML lesson 진행은 건드리지 말고, 별도의 1문제 대화형 학습만 이어가자.
현재 진단은 5문제 중 2문제를 완료했고, current_status.md에 적힌
3번째 문제에 내가 답할 차례다. 유형명과 정답은 먼저 말하지 마.

내가 아래 순서로 답하게 해줘.
1. 문제 유형 추정
2. 주어진 조건
3. 사용할 공식 또는 판단 근거
4. 풀이와 단위
5. 정답 확신도 0~100%

내 답변 뒤에는 개념, 조건 해석, 공식 선택, 계산, 단위, 기억 인출을
나눠 진단해줘. 막히면 정답 대신 힌트를 한 단계씩 주고,
식이 맞으면 계산은 생략해도 된다. 5문제마다 학습 결과를 요약해줘.

비공개 PDF와 source-materials는 GitHub에 없으므로 접근 가능한 척하지 마.
저장소에 기록된 공개 가능한 요약만 사용하고 원문을 복원하거나 추측하지 마.
```

## Next

- Codex Cloud에서는 위 재개용 프롬프트로 별도 대화형 진단 3/5부터 이어간다.
- 직전 레슨 0003의 XOR, 램프 효율, 펌프 출력 공식을 5분간 회상한다.
- lesson 0004는 2024년 1회 16-18번 + 2024년 2회 1-2번의 5문제 세트로 만든다.
- YouTube 강의자료 지도에서 문제 축별 관련 강의를 1개만 연결한다.
- PDF topic index에서 필요한 단답/전기기기/수변전 자료 1개만 골라 오답 포인트를 보강한다.

## Source Safety

- Do not commit paid PDFs, work documents, personal data, or raw source files.
- Record only source name, purpose, and private/local location in `RESOURCES.md`.
- YouTube captions/transcripts and lecture-note originals are not copied into public HTML.
- PDF originals and extracted text stay under ignored `source-materials/`; public pages use rewritten summaries only.
