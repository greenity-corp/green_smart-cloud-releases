# GreenSmart Cloud 공개 안내·릴리즈

Cloud는 GreenSmart의 중앙 관리·데이터 연계를 담당합니다. 이 저장소에는 승인된 Cloud 공개 변경 내역, 지원 조합 안내와 공개 대상으로 승인한 Cloud 산출물만 게시합니다.

- [GreenSmart 전체 안내](https://github.com/greenity-corp/greensmart_release)
- [Cloud Releases](https://github.com/greenity-corp/green_smart-cloud-releases/releases)
- 함께 사용하는 [Edge 안내](https://github.com/greenity-corp/green_smart-edge-releases) · [Controller 안내](https://github.com/greenity-corp/green_smart-controller-releases)

## 현재 게시 상태

2026-10-15 기준 이 GitHub 채널의 Releases는 0개입니다. 이 채널에 공개 릴리즈를 게시하지 않았다는 뜻이며, Cloud가 운영되지 않는다는 뜻은 아닙니다. 검증하지 않은 공개 버전이나 설치 명령을 임의로 안내하지 않습니다.

기존 고객의 설치 파일 전달은 Cloud의 **설치 및 업데이트** 메뉴를 따릅니다. 이 저장소의 공개 안내 추가로 기존 고객 권한과 배포 절차가 바뀌지는 않습니다.

## 공개 릴리즈에 포함할 내용

- Cloud 버전·검토한 원본 커밋 식별자·공개 변경 내역·알려진 제한
- 실제 검증한 Edge·Controller 버전 조합과 필요한 적용 순서
- 고객에게 공개할 설치·업데이트·중단·복구 안내와 지원 조건
- 공개 산출물이 있을 때 그 식별자, SHA-256 체크섬과 서명·출처 검증 방법

Cloud 전용 내용만 게시하고 Edge·Controller 파일은 각 전용 채널로 안내합니다. 소스 코드, 상세 내부 설계, 직원 운영 절차, 내부 주소, 운영 설정, 인증정보와 고객 데이터는 공개하지 않습니다.

## 검증과 출고

태그 형식은 `cloud-vMAJOR.MINOR.PATCH`, 제목은 `Cloud vMAJOR.MINOR.PATCH`를 사용합니다. 이는 표기 규칙이며 현재 지원 버전을 선언하는 예시가 아닙니다.

출고 전에는 Cloud 자체 시험, API 생산자·소비자 계약, 필요한 이전/새 버전 혼용 시험과 통합 회귀를 확인합니다. 고객 화면 변경은 관련 브라우저 E2E 시나리오에 반영합니다. 실제 운영 환경·보안·설치·복구 검증과 출고 승인을 별도로 완료하고, 생략·미실행 항목은 통과로 표시하지 않습니다. 필요한 경우 공개 대상으로 검토한 SBOM·출처 증거를 함께 제공합니다.
