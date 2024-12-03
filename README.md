# .github
**Default MacarongFactory's Community Health File Repository**

이 레포지토리는 조직 내 레포지토리 전반에 적용되는 기본**Community Health File**(템플릿 파일, github action yml 파일 등) 을 제공합니다.

---

## 📋 Included Files
- **`PULL_REQUEST_TEMPLATE.md`**: Pull Request 작성 시 사용하는 기본 템플릿. (하기 내용 참조)
- **`README.md`**: 조직 또는 프로젝트 전반에 대한 설명 문서.
- **`github action`**: Github Action을 사용한 CI/CD 설정 yml 파일. (작업 중)

---

## 🚀 How It Works
- **기본 적용**: `.github` 레포지토리에 포함된 템플릿은 조직 내 대부분의 리포지토리에 자동으로 적용됩니다.
- **적용 제외 Repository**:
    - `backend-assignment` - `backend-assignment`의 특수한 요구 사항이나 커뮤니케이션 방식을 반영하기 위해

---

## 🏷️ How To Write Commit Message and Pull Request

Tag: Message

첫 줄에 태그와 메시지를 작성합니다. 

커밋 메시지는 다음 7개의 태그 중 하나를 사용하여 작성합니다:

### e.g.
- **Feat**: 새로운 기능 추가
  - 예: `feat: Add New function to rule the world.`

- **Mod**: 기존 기능 수정
  - 예: `mod: Add Car factor in Domination.ruleTheWorld().`

- **Ref**: 코드 리팩터링
  - 예: `ref: Extract empathy stuff to an abstract class.`

- **Fix**: 버그 수정
  - 예: `fix: Starvation need to be initialised before Energy to avoid the NPE.`

- **Rem**: 불필요한 코드 제거
  - 예: `rem: freeSpeech is not used anymore.`

- **Perf**: 성능 최적화
  - 예: `perf: Improve query performance by adding indexes to User table.`

- **Rev**: reverting commit
  - 예: `rev: Revert "Add Car factor in Domination.ruleTheWorld()"`
---

### 💡 커밋 메시지 작성 시 참고 사항
1. 첫번째 줄은 명확하고 간략하게 작성하여 코드 이력을 찾아보는 개발자가 한 눈에 알아볼 수 있게 합니다. <br> (히스토리 파악에 사용됩니다.)
2. **태그와 메시지 사이에는 콜론(`:`)과 한 칸의 공백**을 포함합니다. 
3. 태그는 반드시 위의 7개 중 하나를 사용합니다.
4. [Ref Doc](https://google.github.io/eng-practices/review/developer/cl-descriptions.html)