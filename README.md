# AID-X Day

AID-X Day 행사 안내 페이지예요. PC와 모바일 모두에서 보도록 반응형으로 만들었어요.

- 페이지: https://rohminji.github.io/2026-AID-X-Day/
- 구성: 홈 · 프로그램 · 층별 안내 · 셔틀 · 참여 방법 (모바일은 하단 탭, PC는 왼쪽 메뉴)
- 내용 수정: `index.html` 스크립트 상단의 `EVENT` 블록만 고치면 돼요.
  일정(`sessions`), 장소(`rooms`, `floors`), 셔틀(`shuttles`), 참여 방법(`steps`, `faq`), 공지(`notices`)
- 지금은 예시 데이터예요. 실제 정보로 바꾼 뒤 `sample: false`로 바꾸면 상단 안내 띠가 사라져요.
- 행사 당일 화면 미리보기: 주소 뒤에 `?now=2026-10-14T13:20`을 붙이면 그 시각 기준으로 보여줘요.

## 배포 (GitHub Pages)

Settings → Pages → Source: **Deploy from a branch**, Branch: **`main` / `/ (root)`** → Save

## QR 코드 (고정)

`qr/` 폴더의 QR은 아래 주소를 그대로 담은 **정적 QR**이에요. 중간 서비스를 거치지 않아서 QR 자체는 절대 바뀌지 않아요.

    https://rohminji.github.io/2026-AID-X-Day/

주소는 대소문자를 구분해요. QR이 계속 열리려면 행사(10/16)가 끝날 때까지 아래를 **하지 마세요**.

- 저장소 이름 변경 (`2026-AID-X-Day`), GitHub 계정명 변경
- 저장소 삭제 · Private 전환 · Pages 끄기
- `index.html` 파일 이름 변경 또는 삭제

`index.html` 내용 수정은 언제든 괜찮아요. QR은 그대로이고 페이지 내용만 바뀌어요.
