# Pour Guide 커뮤니티

Pour Guide 앱의 커뮤니티 탭 기록이 저장되는 곳이에요. 앱 → 커뮤니티 서버(Cloudflare Worker) → 이 저장소 순서로 저장돼요.

- `challenges.json` 주간 챌린지 레시피. 키는 `연도-W주차`(한국 시간, 월요일 시작), `recipe`는 앱 레시피 이름과 똑같이
- `weeks/<주>.json` 그 주에 올라온 기록 (서버가 자동으로 고쳐요. 손으로 고칠 땐 기록 블록 하나를 통째로 지우는 것만)
