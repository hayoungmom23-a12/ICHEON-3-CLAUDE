# 이천 아이맵 (ICHEON-3-CLAUDE)

이천이 낯선 미취학·저학년 아이 동반 가족이 출발 전에 미리 만든 코스 카드를 열어, 어느 주차장에 대면 원하는 시설로 가기 쉬운지와 시설별 운영시간·휴무·공식 링크를 확인하는 모바일 웹페이지. 기획서 기준 간략화 버전.

현재 단계: 디자인 시안 완료(2026-09-16), 다음은 기능 명세(FRD).

## 디자인 시안

무드: 화이트 체크카드 + 크림 바탕 + 채움 버튼. 모바일 390px 한 열, PC는 가운데 640px 기둥.

- 편집 가능한 캔버스(Claude Design 미리보기, claude.ai 로그인 필요): https://claude.ai/artifact/JFjU1gw62vBnanHWHNmZ8i
- 편집기 없이 바로 열리는 HTML 시안 (내려받아 브라우저로 열기)
  - [01 코스 목록](design/01-코스목록.html)
  - [02 코스 상세](design/02-코스상세.html)
  - [03 하단 안내](design/03-하단안내.html)
  - [04 구성요소와 규칙](design/04-구성요소와규칙.html)
  - [00 무드 비교 (A·B·C와 확정안)](design/00-무드비교.html)
- 캔버스 작업 파일: `design/canvas/` (아트보드 4장 + `canvas.json`), 조립 파일 `design/icheon-imap-screens.html`
- 외부 디자인 도구용 프롬프트: `design/claude-design-프롬프트.txt`, `design/stitch-0*.txt`

카드 안의 진입 방향·운영시간·팁 문장은 모양을 보이기 위한 예시나 `[확인 후 기입]` 자리표시이며, 실제 값은 구현 때 데이터 파일에서 들어간다.

## 문서

- [제품 요구사항 문서 (PRD)](docs/prd.md)
- [디자인 프롬프트와 디자인 시스템](docs/design-prompt.md): 공통 스타일, 참고자료 적용표, 화면별 프롬프트, 시안 분석, 구현용 값
- [과정 설정](docs/setup.md)
- 콘텐츠 작업 폴더: `docs/content/` (방문 팁 모음, 사진 폴더 안내)

## 참고자료

- 이천관광누리집 문화관광 섹션 (https://www.icheon.go.kr/tour/main.do): 정보 구조·카드·지도·코스 체인 등 뼈대만 참고. 로고·색·사진·문구는 쓰지 않음.
