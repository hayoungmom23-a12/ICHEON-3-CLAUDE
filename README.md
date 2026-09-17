# 이천 아이맵 (ICHEON-3-CLAUDE)

이천이 낯선 미취학·저학년 아이 동반 가족이 출발 전에 미리 만든 코스 카드를 열어, 어느 주차장에 대면 원하는 시설로 가기 쉬운지와 시설별 운영시간·휴무·공식 링크를 확인하는 모바일 웹페이지. 기획서 기준 간략화 버전.

현재 단계: 디자인 시안 검토 중(2026-09-18 Claude Design 시안으로 교체), 다음은 기능 명세(FRD).

## 디자인 시안

무드: 화이트 체크카드 + 채움 버튼. 모바일 한 열 구조. 색·글자·간격 값은 [디자인 문서 5절](docs/design-prompt.md)에 있다.

구현 기준 (Claude Design 앱에서 제작, 2026-09-18)

- [01 코스 목록](design/01-코스목록.png)
- [02 코스 상세](design/02-코스상세.png)
- [03 하단 안내](design/03-하단안내.png)

참고 자료 (`design/old/`, 2026-09-16 Claude Code 캔버스 시안)

- 편집 가능한 캔버스(claude.ai 로그인 필요): https://claude.ai/artifact/JFjU1gw62vBnanHWHNmZ8i
- 클릭형 프로토타입 (칩 거르기, 코스 이동, 스팟 카드 펼치기가 동작): [05 프로토타입](design/old/05-프로토타입.html)
- 편집기 없이 바로 열리는 HTML 시안: [01 코스 목록](design/old/01-코스목록.html), [02 코스 상세](design/old/02-코스상세.html), [03 하단 안내](design/old/03-하단안내.html), [04 구성요소와 규칙](design/old/04-구성요소와규칙.html), [00 무드 비교](design/old/00-무드비교.html)
- 캔버스 작업 파일 `design/old/canvas/`, 조립 파일 `design/old/icheon-imap-screens.html`
- 외부 디자인 도구용 프롬프트: `design/old/claude-design-프롬프트.txt`, `design/old/stitch-0*.txt`

시안 속 운영시간·진입 방향·팁 문장은 구현 때 공식 페이지로 다시 확인해 데이터 파일에 넣는다.

## 문서

- [제품 요구사항 문서 (PRD)](docs/prd.md)
- [디자인 프롬프트와 디자인 시스템](docs/design-prompt.md): 공통 스타일, 참고자료 적용표, 화면별 프롬프트, 시안 분석, 구현용 값
- [과정 설정](docs/setup.md)
- 콘텐츠 작업 폴더: `docs/content/` (방문 팁 모음, 사진 폴더 안내)

## 참고자료

- 이천관광누리집 문화관광 섹션 (https://www.icheon.go.kr/tour/main.do): 정보 구조·카드·지도·코스 체인 등 뼈대만 참고. 로고·색·사진·문구는 쓰지 않음.
