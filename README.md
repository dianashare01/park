# 마리서사 시 낭송 — 방문객 재생 페이지

키오스크(유니티 park 프로젝트)에서 받은 QR 을 휴대폰으로 찍으면 열리는 페이지입니다.
주소: https://dianashare01.github.io/park/?id=녹음ID

- 녹음 파일은 Supabase Storage(recordings 버킷)에 있고, 이 페이지는 재생·내려받기·공유만 합니다.
- index.html 맨 위 설정(SUPABASE_URL, KEY=publishable 키, POEMS)만 고치면 됩니다. secret 키는 절대 넣지 마세요.
