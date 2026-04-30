# devlog

학습 unit을 글감으로 처리하는 폴더 구조.
운영 룰은 [CLAUDE.md](./CLAUDE.md).

## 구조

```
devlog/
├─ CLAUDE.md          ← 운영 룰 + AI 협업 가드레일
├─ README.md          ← 이 파일
├─ roadmap.md         ← 학습 로드맵 + 글감 진행 순서 (SSOT)
├─ scratch.md         ← raw brain dump
├─ 00 inbox/          ← 모르는 거 (한 항목 = 한 .md)
├─ 01 doing/          ← 지금 보고 있는 1~2개
└─ 02 done/           ← 정제 끝, 블로그 backlog
```

## 흐름

```
00 inbox → (호기심·필요 순으로 픽) → 01 doing → 학습 + 정리 → 02 done
```

## 사용법

1. 이 repo fork 또는 clone
2. `roadmap.md` 본인 학습 영역으로 갱신
3. `00 inbox/`에 본인 학습 거리 채우기 (`EXAMPLE-template.md` 형식 참고)
4. AI(Claude / Cursor / 다른 도구) 옆에 두고 `CLAUDE.md` 룰 따라 운영
5. `02 done/`에 5개 정도 쌓이면 발행처 결정
