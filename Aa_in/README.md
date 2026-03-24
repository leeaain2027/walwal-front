```
walwal (web)     ← FastAPI + 프론트 서빙
walwal-agent (worker) ← agent_worker.py 폴링 루프
Render 대시보드에서 walwal-agent 서비스에 환경변수 추가 필요:

OPENAI_API_KEY → 실제 키
RENDER_URL → https://walwal-ke0m.onrender.com (실제 URL)
로컬에서 테스트하려면:


RENDER_URL=http://localhost:8000 python agent_worker.py
```

