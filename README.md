# crepax-uptime

[크레팍스](https://crepax.co.kr) 보조 장애 감시. 15분마다 `/api/v1/health` 와 홈을 확인하고,
실패하면 GitHub 가 메일로 알립니다. 주 감시(1분 · 관리자 문자)는 Supabase 크론이며,
이 저장소는 그것까지 멈춘 경우(DB 장애)를 대비합니다. 비밀값 없음.
