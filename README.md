# 이력서

## 링크

Github: https://github.com/limsoha

E-mail: soha0710@gmail.com

링크드인: https://www.linkedin.com/in/%EC%86%8C%ED%95%98-%EC%9E%84-2077921a4/

## 경력
10년 차 안드로이드 앱 개발자. Kotlin 기반으로 앱 개발 경험 보유.  
Jetpack Compose, Navigation Component, Hilt 등을 활용해 모듈화 및 아키텍처 개선에 기여.  
MAU 90만 이상 서비스의 안정적인 운영을 위한 유지보수, 코드 리팩터링 및 신규 기능 런칭 경험.

[아데나소프트웨어](https://www.adenasoft.com/ko-KR/)
  - 팀원 2021.12.21 ~

[오케이인베스트먼트파트너스](http://okfngroup.com)
  - 계장 2020.06.01 ~ 2021.12.01

[티월드글로벌](http://t-chain.io/)
  - 주임 2018.11.01 ~ 2020.05.29

[이엠디넷](http://www.emdinet.com/)
  - 사원 2015.10.01 ~ 2018.09.20

## 기술 스택
- 언어: Kotlin
- 아키텍처: MVVM, MVI, Clean Architecture
- 프레임워크/라이브러리: Coroutines, Flow, Ktor, Hilt, Jetpack (Compose, Paging3, Room, Navigation), Coil, Glide, etc.
- CI/CD: Firebase App Distribution, Fastlane
- 툴: Android Studio, Figma, Height
- 기타: Firebase, REST API
  
## 회사프로젝트

### 코인니스
코인 관련 속보, 마켓 정보 등을 제공하는 커뮤니티 서비스

- 소속 : 아데나소프트웨어
- 기간 : 2021.12 ~ 
- 역할 : Android 앱 설계 및 신기능 개발 리드
- 기술 스택 : Kotlin, Compose, Hilt, Ktor, Coroutine, Flow, Firebase 등
- 주요 업무 및 성과:
    - 입사 당시 설치 수 5만 명 규모의 앱을 안정적인 운영 및 기능 확장을 통해 현재 18만 명 이상으로 성장하는 과정에 기여
    - 유지보수 및 리팩터링 주도: 코드 품질 개선과 구조 고도화를 통해 장기적인 유지보수 비용 절감 및 개발 효율성 확보
    - 신규 기능 런칭
      - 소셜 로그인(카카오/네이버/구글) 추가: 가입 플로우 다양화 및 신규 유입 확대 지원
      - 푸시 알림 고도화: 기존에 분리되어 있던 푸시 페이로드 처리 방식과 딥링크 처리 방식을 통합하여 중복 코드 제거, 일관성 확보, 소스 코드 관리 및 유지보수 효율성 향상
      - 다크 모드 지원: 사용자 경험 개선 및 최신 OS 트렌드 반영
      - 다국어 앱 지원(Multi-language) → 글로벌 사용자 접근성 확대 및 앱 확장성 강화
    - 핵심 리팩터링 및 아키텍처 개선
        - UI: 기존 XML 화면을 Jetpack Compose로 단계적 전환(약 70%), 개발 생산성 향상 및 UI 유지보수 비용 절감
        - DI: Koin → Hilt 마이그레이션으로 공식 지원 기반 DI 체계 확립, 테스트 및 의존성 관리 용이성 확보
        - 아키텍처: Clean Architecture 적용, 관심사 분리 및 모듈 간 의존성 최소화로 확장성과 안정성 강화
    - 배포 프로세스 자동화: Fastlane을 활용해 Firebase App Distribution(Staging)과 Play Store(Prod) 배포 자동화, 배포 시 Slack 알림 및 Git Tag 생성 연동으로 배포 효율성 향상
    - Play Store(https://play.google.com/store/apps/details?id=live.coinness&hl=ko)

### 올리고

P2P 투자, e금・e은 투자 등 투자와 송금서비스 및 이벤트를 통한 포인트를 제공하는 재테크 서비스

- 소속 : 오케이인베스트먼트파트너스
- 역할 : Android 앱 신서비스 대응 및 legacy 개선
 + MVC -> MVVM
 + Java -> Kotlin
 + NavigationView -> BottomNavigationView
 + library 최신 적용 (androix, firebase crashlytics 등)
 
#### Android

<img src ="https://user-images.githubusercontent.com/48788456/114798209-cee77b00-9dcf-11eb-910e-b63dfa98270d.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/114798219-d27b0200-9dcf-11eb-9a10-2b4d45ecc715.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/114798221-d4dd5c00-9dcf-11eb-87e3-a3340388042d.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/114798224-d60e8900-9dcf-11eb-8f00-bdaf3f336b36.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/114798226-d73fb600-9dcf-11eb-8bcd-14798e915ddf.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/114798227-d7d84c80-9dcf-11eb-8d33-775a04520b56.png" width="250">

- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, Java, xml, RxKotlin, RxAndroid
- 아키텍처 : MVVM, MVC
- Play Store(https://play.google.com/store/apps/details?id=com.apro.cereal)

#### Web (서비스앱/괸라지페이지)

- 개발환경 : Window OS, IntelliJ, DBeaver
- 사용기술 : Spring Famework, Java, javascript, MySql

### HuChain

HuChain 사에서 사용할 지갑 및 회원정보 관리 앱

- 소속 : 티월드글로벌
- 역할 : Android, iOS 앱 개발

#### Android

<img src ="https://user-images.githubusercontent.com/48788456/74133967-01767080-4c2d-11ea-994e-1eefca48dd5c.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74133892-e60b6580-4c2c-11ea-8c06-5e2f935fda2d.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74135600-ebb67a80-4c2f-11ea-9c7e-d9863d14ece6.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74135604-ef4a0180-4c2f-11ea-81c2-f73f776d8605.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74135606-efe29800-4c2f-11ea-9d9f-fefa41f61bec.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74135607-f07b2e80-4c2f-11ea-9e66-102e0d401ec1.png" width="250">

- 개발기간 : 2019.12.30 ~ 2020.01.29
- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml, RxKotlin, RxAndroid
- 아키텍처 : MVVM
- Play Store(https://play.google.com/store/apps/details?id=com.huchain.huchain)

#### iOS

<img src ="https://user-images.githubusercontent.com/48788456/74220922-339ed580-4cf4-11ea-9a25-0fb982c9ef48.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74220917-313c7b80-4cf4-11ea-9e5e-52f0a3fe56dd.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74221401-65646c00-4cf5-11ea-9a73-a92c02a777ae.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74221406-685f5c80-4cf5-11ea-9966-3882daf4954a.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74221408-68f7f300-4cf5-11ea-9a21-a15e966d79f9.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74221410-69908980-4cf5-11ea-88d6-41c35e4d8ea0.png" width="250">  

- 개발기간 : 2020.01.13 ~ 2020.01.30
- 개발환경 : MacOS, XCode, Zeplin
- 사용기술 : iOS, Swift
- 아키텍처 : VIPER
- App Store(https://apps.apple.com/us/app/%ED%9C%B4%EC%B2%B4%EC%9D%B8-huchain/id1495921341)

### Kan Tong

인도네시아에서 사용할 Tong 지갑 앱

<img src ="https://user-images.githubusercontent.com/48788456/74398616-965eb100-4e5b-11ea-91cf-7aff13820e95.jpg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74398620-9a8ace80-4e5b-11ea-9f95-0d0ca0382061.jpg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74398668-c1490500-4e5b-11ea-8f64-ba8f38bd89d2.jpg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74398627-a1b1dc80-4e5b-11ea-9693-b2a8af0d2d13.jpg" width="200">   

- 소속 : 티월드글로벌
- 역할 : Android 앱 개발
- 개발기간 : 2019.11.21 ~ 2019.12.02
- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml
- 아키텍처 : MVP
- Play Store(https://play.google.com/store/apps/details?id=com.tworldglobal.kantong)

### Sharp Coin

<img src ="https://user-images.githubusercontent.com/48788456/74398081-cb6a0400-4e59-11ea-90e5-b23bcba64b18.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74398088-cf962180-4e59-11ea-94ad-d35c1271da6c.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/74398090-d15fe500-4e59-11ea-8c60-a92078070a32.png" width="250">  

Shrp Coin 지갑 앱

- 소속 : 티월드글로벌
- 역할 : Android 앱 개발
- 개발기간 : 2019.10.08 ~ 2019.10.17
- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml
- 아키텍처 : MVP
- Play Store(https://play.google.com/store/apps/details?id=com.tworldglobal.sharpcoin)

### 소비연금제 협동조합

<img src ="https://user-images.githubusercontent.com/48788456/75009840-fb02b700-54be-11ea-8e68-cadf786517c1.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/75009824-f3431280-54be-11ea-8b83-883a4deacece.png" width="250">  

소비연금제 협동조합 쇼핑몰 하이브리드 앱

- 소속 : 티월드글로벌
- 역할 : Android 하이브리드 앱 개발
- 개발기간 : 2019.07.10 ~ 2019.08.20
- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml
- 아키텍처 : MVP
- Play Store(https://play.google.com/store/apps/details?id=com.tworldglobal.twomart)

### 1in2

<img src ="https://user-images.githubusercontent.com/48788456/75010703-2686a100-54c1-11ea-8027-03ca0b1073c8.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/75010717-30100900-54c1-11ea-90ab-4874a4919eea.png" width="250">  <img src ="https://user-images.githubusercontent.com/48788456/75010726-343c2680-54c1-11ea-9dc9-f7e3c65ee46b.png" width="250">  

1in2 쇼핑몰 하이브리드 및 QR 적립기능이 있는 앱

- 소속 : 원인투 (티월드글로벌 외주)
- 역할 : Android, iOS 앱 개발

#### Android

- 개발기간 : 2019.03.21 ~ 2019.07.11
- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml, Room
- 아키텍처 : MVP
- Play Store(https://play.google.com/store/apps/details?id=com.tfriend.oneintwo)

#### iOS

- 개발기간 : 2019.03.21 ~ 2019.07.11
- 개발환경 : MacOS, XCode, Zeplin
- 사용기술 : iOS, Swift
- 아키텍처 : VIPER
- App Store(https://apps.apple.com/kr/app/1in2-%EC%9B%90%EC%9D%B8%ED%88%AC/id1468246386)

### TK Pay

TK Mall 에서 사용하는 TK Pay 지갑 앱

- 소속 : 티월드글로벌
- 역할 : Android, iOS 앱 개발

#### Android

<img src ="https://user-images.githubusercontent.com/48788456/75009148-4a47e800-54bd-11ea-9e82-a93e86c7c856.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/80440400-ac045280-8943-11ea-9c06-fe9a112bf0d7.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009113-297f9280-54bd-11ea-80e1-a04ded71fe12.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009110-28e6fc00-54bd-11ea-9c51-90de83bcfd37.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009111-297f9280-54bd-11ea-973a-66d1e7bb1c78.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009114-2a182900-54bd-11ea-8c35-e4abb4f82f75.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009109-284e6580-54bd-11ea-85c6-4cb4de3a0292.png" width="200">  

- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml
- 아키텍처 : MVP
- Play Store(https://play.google.com/store/apps/details?id=com.tworldglobal.tkpay)

#### iOS

<img src ="https://user-images.githubusercontent.com/48788456/75009335-c4786c80-54bd-11ea-9a56-5d779cec6e93.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/80440400-ac045280-8943-11ea-9c06-fe9a112bf0d7.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009337-c5110300-54bd-11ea-9550-d8d5775c9181.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/75009338-c5a99980-54bd-11ea-9090-a411092f8ae7.png" width="200">  

- 개발환경 : MacOS, XCode, Zeplin
- 사용기술 : iOS, Swift
- 아키텍처 : VIPER
- App Store(https://apps.apple.com/us/app/tk-pay/id1470201264)

### Tong Pay

Tong Pay는 T world global에서 개발한 Tong Coin으로 전송, 결제 및 내역 조회를 할 수 있는 앱입니다.

- 소속 : 티월드글로벌
- 역할 : Android, iOS 앱 개발

#### Android

<img src ="https://user-images.githubusercontent.com/48788456/74696541-342af500-523b-11ea-801b-e2b896742191.jpg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74696549-38571280-523b-11ea-9709-67d8305ed731.jpg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74696560-4016b700-523b-11ea-91b0-cbfabae33d43.jpg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74696571-4ad14c00-523b-11ea-87ad-23e2dcb929ef.jpg" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/73923236-dd095400-490d-11ea-823b-585a8fddd2c8.png" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/73923124-b1866980-490d-11ea-9e4a-0c30a059e459.png" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/73923172-c236df80-490d-11ea-8fb9-d4efc8b01e62.png" width="200">   

- 개발환경 : MacOS, Android Studio, Zeplin
- 사용기술 : Android, Kotlin, xml
- 아키텍처 : MVP
- Play Store(https://play.google.com/store/apps/details?id=io.tchain.tong.pay)

#### iOS

<img src ="https://user-images.githubusercontent.com/48788456/74008550-7eeb7800-49c4-11ea-8002-9be7223d95b4.jpeg" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74008648-b8bc7e80-49c4-11ea-956f-8ce7a18a4370.png" width="200">  <img src ="https://user-images.githubusercontent.com/48788456/74008710-e30e3c00-49c4-11ea-9ed7-1b9d2596cf75.png" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/74008735-f4efdf00-49c4-11ea-8dd8-8bdc3f317d27.png" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/74016426-c8908e80-49d5-11ea-8942-eab9f1a2fce3.png" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/74016445-cfb79c80-49d5-11ea-82b4-dea157965337.png" width="200">   <img src ="https://user-images.githubusercontent.com/48788456/74016434-caf2e880-49d5-11ea-92be-0914ab26aaed.png" width="200">   

- 개발환경 : MacOS, XCode, Zeplin
- 사용기술 : iOS, Swift
- 아키텍처 : VIPER
- App Store(https://apps.apple.com/us/app/tong-pay/id1448340953)
