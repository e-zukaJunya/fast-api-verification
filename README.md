# FastAPI Verification

Gunicorn推奨

## Overview

```ini
COMPOSE_PROJECT_NAME="fast-api-test"
```

## Tips

uvicorn sample:app --reload
uvicorn src.sample:app --reload
<!-- ホストとport forwardingする場合 -->
uvicorn src.sample:app --reload --host 0.0.0.0 --port 8000
