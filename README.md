# MDAC Autofill

말레이시아 디지털 입국카드(MDAC)에 자주 쓰는 정보를 저장하고 다시 채우는 데스크톱 Chrome용 북마클릿입니다.

A bookmarklet for desktop Chrome that saves and fills your usual details in the Malaysia Digital Arrival Card (MDAC).

[설치 페이지 / Install page](https://solpop-arch.github.io/mdac-autofill/) · [공식 등록 페이지 / Official registration form](https://imigresen-online.imi.gov.my/mdac/main?registerMain)

## 설치 및 사용

1. 설치 페이지에서 **MDAC 채우기 / Fill MDAC** 버튼을 북마크바로 끌어다 놓습니다. 끌어 놓기가 안 되면 **주소 복사 / Copy URL**를 누르고 새 북마크의 URL 칸에 붙여넣습니다.
2. 공식 등록 페이지에서 처음 한 번은 기본 정보를 직접 입력합니다. 북마크를 누르고 확인하면 입력한 정보가 저장됩니다.
3. 다음부터는 등록 페이지에서 북마크를 누르고 확인하면 저장한 정보가 채워집니다.
4. 입국일·출국일·편명은 매번 직접 입력합니다. 내용을 확인한 뒤 캡차를 풀고 제출합니다.

저장한 정보를 바꾸려면 폼에 새 값을 입력하고 북마크를 누른 뒤 **취소 → 확인**을 선택합니다.

## Install and use

1. On the install page, drag **MDAC 채우기 / Fill MDAC** to your bookmarks bar. If dragging does not work, click **Copy URL** and paste it into a new bookmark’s URL field.
2. On your first visit to the official registration form, enter your usual details by hand. Click the bookmark and confirm to save them.
3. On later visits, click the bookmark and confirm to fill the form with your saved details.
4. Enter arrival/departure dates and your flight number each time. Review the form, complete the captcha, and submit it yourself.

To update saved details, enter the new values in the form, click the bookmark, then choose **Cancel → OK**.

## 개인정보 / Privacy

저장한 정보는 Chrome의 공식 MDAC 사이트 저장소(localStorage)에만 남습니다. 북마클릿은 정보를 서버로 전송하지 않으며, 공식 MDAC 도메인에서만 작동합니다. 해당 사이트의 데이터를 지우면 저장한 정보도 삭제됩니다.

Saved details stay in Chrome’s localStorage for the official MDAC site. The bookmarklet does not send them to a server and only runs on the official MDAC domain. Clearing that site’s data also clears the saved details.

## 검증 및 제한 / Testing and limitations

공식 사이트의 방화벽이 헤드리스 브라우저를 차단하여, 내려받은 페이지와 모의 서버 응답으로 테스트했습니다. 폼이 바뀌어 저장한 선택지를 찾지 못하면 해당 칸을 알려 줍니다. 캡차 해결과 제출은 사용자가 직접 합니다.

The official site’s firewall blocked headless browser access, so testing used a downloaded page and simulated server responses. If a saved option is unavailable after the form changes, the bookmarklet reports the affected field. You complete the captcha and submit the form yourself.
