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
  "python.analysis.includeAliasesFromUserFiles": true,
  "python.analysis.importFormat": "absolute",
  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter",
  },
```
<img width="500" height="178" alt="image" src="https://github.com/user-attachments/assets/be686485-3212-45cd-a2d4-4dbcc9d6fd14" />

| 설정                                                   | 기능                                 |
| ---------------------------------------------------- | ---------------------------------- |
| `typeCheckingMode: standard`                         | 기본 수준의 정적 타입 검사 활성화                |
| `autoImportCompletions: true`                        | 자동완성 시 필요한 Import 후보 제공            |
| `indexing: true`                                     | 프로젝트 및 설치 패키지의 심볼 색인               |
| `completeFunctionParens: true`                       | 함수 자동완성 시 괄호 자동 추가                 |
| `includeAliasesFromUserFiles: true`                  | 사용자 파일에서 재노출한 심볼도 자동 Import 후보에 포함 |
| `importFormat: absolute`                             | 절대 경로 Import 형식 사용                 |
| `editor.defaultFormatter: ms-python.black-formatter` | Python 파일의 기본 포매터를 Black으로 지정      |

### 실사용 예시

<img width="941" height="107" alt="image" src="https://github.com/user-attachments/assets/29c92516-4fc3-48c8-af57-6201df66db0f" />

- 자동 임포팅(`ctrl+space`)
