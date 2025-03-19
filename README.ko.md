# 여유로 (SeoulFlow)

<p align="center">
  <a href="README.md">English</a> | <a href="README.ko.md">한국어</a>
</p>

<p align="center">
  <img src="src/assets/logo.png" alt="SeoulFlow Logo" width="200"/>
</p>

<p align="center">
  <b>지하철 실시간, 혼잡도, 최적 방문시간</b>
</p>

<!-- <p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.seoulflow.app"><img src="assets/google-play-badge.png" alt="Google Play에서 다운로드" height="40"></a>
  <a href="https://apps.apple.com/app/seoulflow/id1234567890"><img src="assets/app-store-badge.png" alt="App Store에서 다운로드" height="40"></a>
  <a href="https://seoulflow.app"><img src="assets/web-badge.png" alt="웹 앱 열기" height="40"></a>
</p> -->

## 소개

여유로는 수도권 지하철의 실시간 위치 및 혼잡도 정보와 함께 주요 장소의 방문 최적 시간을 제공하는 앱입니다. 지하철 칸별 혼잡도 예측과 쇼핑몰, 관광지의 혼잡 정보를 통해 사용자가 더 편안하게 이동하고 방문할 수 있도록 도와줍니다.

## 주요 기능

### 지하철 정보

- 📍 수도권 지하철 실시간 위치 추적
- 🔍 역명 검색 및 즐겨찾기 기능
- ⏱️ 실시간 도착 정보 제공
- 📊 지하철 칸별 혼잡도 예측

### 장소 정보

- 🏙️ 수도권 내 쇼핑, 여가 장소 혼잡도 정보
- 🕒 특정 장소 최적 방문 시간대 추천
- 📈 각 장소의 방문자 추이 확인

### 예정된 기능

- 🗺️ 대한민국 여행 데이터 정보 제공
- 🔄 지역 별 인기 여행지 및 방문 패턴 분석

<!-- ## 스크린샷

<p align="center">
  <img src="assets/screenshots/screenshot1.png" width="200" alt="실시간 지하철 위치 및 혼잡도">
  <img src="assets/screenshots/screenshot2.png" width="200" alt="장소 혼잡도 및 최적 방문 시간">
  <img src="assets/screenshots/screenshot3.png" width="200" alt="즐겨찾기 및 검색 기능">
  <img src="assets/screenshots/screenshot4.png" width="200" alt="방문자 추이 분석">
</p> -->

## 기술 스택

- **프론트엔드**: [Lynx](https://lynxjs.org/) - Android, iOS, 웹 크로스 플랫폼 지원
- **API 통합**:
  - 서울 교통공사 Open API
  - 한국관광공사 Tour API
  - SK open API
  - 기타 혼잡도 데이터 소스

## 설치 및 개발

### 개발 환경 설정

```bash
# 저장소 클론
git clone https://github.com/jaem1n207/seoul-flow.git
cd seoul-flow

# 의존성 설치
pnpm install

# 개발 서버 실행
pnpm run dev
```

LynxExplorer 앱으로 단말기의 QR 코드를 스캔하면 결과를 볼 수 있습니다.
`src/App.tsx` 파일을 수정하여 페이지 편집을 시작할 수 있습니다. 파일을 편집하면 페이지가 자동으로 업데이트됩니다.

## 기여 방법

여유로 개발에 기여하고 싶으시다면 다음 절차를 따라주세요:

1. 이 저장소를 포크합니다.
2. 새로운 기능 브랜치를 생성합니다 (git checkout -b feature/amazing-feature).
3. 변경사항을 커밋합니다 (git commit -m 'Add some amazing feature').
4. 브랜치에 푸시합니다 (git push origin feature/amazing-feature).
5. Pull Request를 생성합니다.

자세한 기여 가이드라인은 [CONTRIBUTING.md](./CONTRIBUTING.ko.md)를 참조하세요.

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 LICENSE 파일을 참조하세요.

## 연락처

- 프로젝트 관리자: [tech.jmtt@gmail.com](mailto:tech.jmtt@gmail.com)
- 웹사이트: [https://bendd.me/](https://bendd.me/)
- 이슈 트래커: [GitHub Issues](https://github.com/jaem1n207/seoul-flow/issues)

<p align="center">
  여유로 - 더 여유롭게 서울을 즐기세요!<br>
  ❤️
</p>
