# MDAC Autofill

말레이시아 디지털 입국카드(MDAC) 기본 정보를 한 번에 채우는 크롬 북마클릿.
A Chrome bookmarklet that fills your usual details into the Malaysia Digital Arrival Card.

**설치 페이지 / Install page: https://solpop-arch.github.io/mdac-autofill/**

- 처음 한 번 직접 입력하고 북마크를 누르면 저장, 다음부터는 누르면 채운다. 날짜·편명·캡차·제출은 직접 한다.
- 값은 내 크롬의 MDAC 사이트 localStorage에만 남는다. 서버로 보내지 않고, 공식 도메인이 아니면 작동하지 않는다.
- 사이트가 붙여넣기를 막지만 값을 직접 넣으므로 상관없다. 캡차 우회와 자동 제출은 하지 않는다.
- 사이트 방화벽이 헤드리스 브라우저를 막아서, 시험은 받아 둔 페이지와 가짜 서버 응답으로 했다(2026-09-28). 폼이 바뀌면 "선택지를 못 찾은 칸"으로 알려 준다.
