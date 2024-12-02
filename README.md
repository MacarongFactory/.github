# .github
**Default MacarongFactory's Community Health File Repository**

이 레포지토리는 조직 내 리포지토리 전반에 적용되는 기본 **커뮤니티 건강 파일**(템플릿 파일 등)을 제공합니다.

---

## 📋 포함된 파일
- **`PULL_REQUEST_TEMPLATE.md`**: Pull Request 작성 시 사용하는 기본 템플릿. (하기 내용 참조)
- **`README.md`**: 조직 또는 프로젝트 전반에 대한 설명 문서.
- **`github action`**: Github Action을 사용한 CI/CD 설정 파일. (작업 중)

---

## 🚀 적용 방식
- **기본 적용**: `.github` 레포지토리에 포함된 템플릿은 조직 내 대부분의 리포지토리에 자동으로 적용됩니다.
- **적용 제외 리포지토리**:
    - `backend-assignment` - `backend-assignment`의 특수한 요구 사항이나 커뮤니케이션 방식을 반영하기 위해

---

## 🏷️ Git Commit Tag 종류 (6개로 한정)

커밋 메시지는 다음 6개의 태그 중 하나를 사용하여 작성합니다:

Tag: Message

### e.g.
- **Feat**: 새로운 기능 추가
  - 예: `Feat: Add New function to rule the world.`

- **Mod**: 기존 기능 수정
  - 예: `Mod: Add Car factor in Domination.ruleTheWorld().`

- **Ref**: 코드 리팩터링
  - 예: `Ref: Extract empathy stuff to an abstract class.`

- **Fix**: 버그 수정
  - 예: `Fix: Starvation need to be initialised before Energy to avoid the NPE.`

- **Rem**: 불필요한 코드 제거
  - 예: `Rem: freeSpeech is not used anymore.`

- **Perf**: 성능 최적화
  - 예: `Perf: Improve query performance by adding indexes to User table.`

---

### 💡 커밋 메시지 작성 시 참고 사항
1. **태그와 메시지 사이에는 콜론(`:`)과 한 칸의 공백**을 포함합니다.
2. 메시지는 간결하고 명확하게 summary 를 작성합니다. (히스토리 파악에 사용됩니다.)
3. 태그는 반드시 위의 6개 중 하나를 사용합니다.