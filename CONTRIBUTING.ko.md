# 기여 가이드라인

<p align="center">
  <a href="README.ko.md">한국어</a> | <a href="README.md">English</a>
</p>

여유로(SeoulFlow) 프로젝트에 관심을 가져주셔서 감사합니다! 이 문서는 프로젝트에 기여하는 방법에 대한 가이드라인을 제공합니다.

## 이슈 보고

버그를 발견하거나 새로운 기능을 제안하려면 [GitHub 이슈 트래커](https://github.com/jaem1n207/seoul-flow/issues)를 사용해주세요:

1. 먼저 이미 보고된 이슈인지 확인합니다.
2. 새로운 이슈를 생성할 때는 가능한 한 자세한 정보를 제공하세요:
   - 버그의 경우: 재현 단계, 예상 동작, 실제 동작, 스크린샷, 디바이스/OS 정보
   - 기능 제안의 경우: 상세한 설명과 가능한 구현 방법, 사용 사례

## 개발 프로세스

1. 저장소를 포크하고 로컬에 클론합니다.
2. 새로운 브랜치를 생성합니다 (feature/xxx, bugfix/xxx, etc).
3. 코드 스타일 가이드를 따라 코드를 작성합니다.
4. 테스트를 추가하고 모든 테스트가 통과하는지 확인합니다.
5. Pull Request를 제출합니다.

## 코드 스타일 가이드

- TypeScript/JavaScript 코드는 ESLint와 Prettier 설정을 따릅니다.
- 컴포넌트는 기능별로 분리하여 구성합니다.
- 모든 함수와 중요 변수에 주석을 추가합니다.
- 커밋 메시지는 영어로 작성하며, 다음 형식을 따릅니다:
  - `feat: Add new feature`
  - `fix: Fix bug in...`
  - `docs: Update documentation`
  - `style: Format code`
  - `refactor: Refactor code without changing functionality`
  - `test: Add or update tests`
  - `chore: Update build process or auxiliary tools`

## Pull Request 프로세스

1. PR 제목은 변경 사항을 간결하게 설명해야 합니다.
2. PR 설명에는 변경 사항과 그 이유를 자세히 설명해주세요.
3. 코드 리뷰가 완료되면 프로젝트 관리자가 승인 및 병합합니다.
4. 병합 후 관련 이슈가 있으면 자동으로 닫히도록 PR에 "Closes #issue_number" 형식으로 언급합니다.

<!-- ## 번역 기여

앱의 다국어 지원을 위한 번역 기여도 환영합니다:

1. `src/assets/locales/` 디렉토리에서 번역 파일을 찾습니다.
2. 새로운 언어를 추가하거나 기존 번역을 개선합니다.
3. 번역이 완료되면 PR을 제출합니다. -->

## 코드 리뷰

모든 제출물은 코드 리뷰를 통과해야 합니다. 리뷰어는 다음을 확인합니다:

- 코드 품질과 가독성
- 테스트 커버리지
- 기능 요구사항 충족 여부
- 코드 스타일 가이드 준수 여부

## 감사의 말

여유로(SeoulFlow)에 기여해주신 모든 분들께 감사드립니다. 여러분의 지원과 기여가 더 나은 서비스를 만드는 데 큰 도움이 됩니다.
