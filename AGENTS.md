# 작업 규칙

- 기능 구현 또는 수정 후 pytest 테스트를 작성하거나 갱신한다.
- 반드시 `.\.venv\Scripts\python.exe -m pytest`를 실행한다.
- 테스트가 통과하면 `git status`와 `git diff`를 확인한다.
- `.venv`, `__pycache__`, `.pytest_cache`, 비밀키와 `.env` 파일은 Git에 올리지 않는다.
- 변경 사항을 명확한 커밋 메시지로 커밋하고 `origin/main`에 push한다.
- 마지막 응답에는 변경 사항, 테스트 결과, 커밋 해시, push 결과, 실행할 파일을 요약한다.
