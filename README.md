# Lemmings

원작 **Lemmings (1991)** 의 *Fun* 티어 9개 레벨을 그대로 옮긴 단일 HTML 클론 게임입니다.
스킬을 고르고 레밍을 탭/클릭해 출구로 인도하세요.

▶ **플레이: https://applepang-cloud.github.io/lemmings2/**

## 레벨 (원작 Fun 1~13)

| # | 레벨명 | 스킬 | 구출 목표 |
|---|--------|------|-----------|
| 1 | Just dig! | 굴착 ×10 | 1 / 10 |
| 2 | Only floaters can survive this | 낙하산 ×10 | 1 / 10 |
| 3 | Tailor-made for blockers | 차단 ×10 | 5 / 50 |
| 4 | Now use miners and climbers | 등반 ×10 · 대각굴 ×1 | 10 / 10 |
| 5 | You need bashers this time | 수평굴 ×50 | 5 / 50 |
| 6 | A task for blockers and bombers | 폭파 ×5 · 차단 ×5 | 10 / 50 |
| 7 | Builders will help you here | 건설 ×20 | 25 / 50 |
| 8 | Not as complicated as it looks | 전 스킬 ×20 | 95 / 100 |
| 9 | We all fall down | 굴착 ×20 | 20 / 20 |

레벨 데이터(레벨명·스킬 수·구출 목표·제한시간·생성속도)는
[Willicious/RetroLemmini](https://github.com/Willicious/RetroLemmini) 의 원본 `.rlv` 파일을 참고했습니다.

## 스킬

등반(Climber) · 낙하산(Floater) · 폭파(Bomber) · 차단(Blocker) · 건설(Builder) · 수평굴(Basher) · 대각굴(Miner) · 굴착(Digger)

## 기술

순수 HTML/CSS/JavaScript, Canvas 2D. 외부 라이브러리·빌드 도구 없음. `index.html` 하나로 동작합니다.

## 로컬 실행

```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1 -Port 8855
# http://localhost:8855/
```
