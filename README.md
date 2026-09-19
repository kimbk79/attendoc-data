# attendoc-data

AttenDoc 앱이 내려받는 논문 학습 데이터입니다.

- `manifest.json` — 논문 목록과 버전, 파일 크기·SHA-256
- `roadmap.json` — 0~12단계 학습 로드맵
- `papers/<id>/paper.json` — 문장별 원문·직독직해·번역·핵심 어휘·기술 해설
- `papers/<id>/voca.json` — 논문별 단어장

앱의 데이터 서버 주소는 이 저장소의 raw 경로입니다.
이 폴더는 원본 프로젝트의 `tools/publish_data.py`가 만듭니다. 직접 고치지 마세요.
