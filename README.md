# 파이썬 세팅
### 1. 'python' 확장 프로그램 설치

<img width="493" height="492" alt="image" src="https://github.com/user-attachments/assets/38fd486e-fc43-425d-b6f2-3a3d58114d23" />

[python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

### 2. 유저 설정 파일
- `ctrl+shift+p` 입력후 유저 설정(json) 열기

<img width="822" height="107" alt="스크린샷 2026-11-26 172109" src="https://github.com/user-attachments/assets/f5ab73a7-d469-48f2-b911-2cee5f07ce1e" />

### 2-1. 파이썬 관련 설정 입력
```json
  "python.analysis.typeCheckingMode": "standard",
  "python.analysis.autoImportCompletions": true,
  "python.analysis.indexing": true,
  "python.analysis.completeFunctionParens": true,
  "python.analysis.includeAliasesFromUserFiles": true,
  "python.analysis.importFormat": "absolute",
  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter",
  },
```
<img width="507" height="247" alt="스크린샷 2026-11-26 172130" src="https://github.com/user-attachments/assets/6960c960-4589-4527-9077-cd3e646c2717" />

### 실사용 예시
