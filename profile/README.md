# 편의점 할인 정보 통합 조회 서비스 : 편킹

    💡 편의점마다 다른 수많은 행사 상품.. 어디서 사는게 가장 저렴할까? 편킹에서 찾아봐야지~!

## 핵심 기능

### 추천 상품 목록
    💡 서비스 사용자의 행동을 분석해 맞춤으로 추천 상품 목록을 제공합니다!
관련 이미지 스샷 (gif)
### 이미지 검색 기능(베타)
    💡 상품의 사진을 찍으면 해당 상품에 대한 할인 정보를 제공합니다!
관련 이미지 스샷 (gif)

## 시스템 아키텍처
### 전체 시스템 다이어그램
<img src="/profile/system_diagram.png">

### 모듈 레포지토리
1. [비즈니스 로직 서버](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTONE_DESIGN_BackEnd_API_Server)
2. [상품 인식 모듈](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTONE_DESIGN_AI_Module)
3. [데이터 수집 모듈](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTONE_DESIGN_BackEnd_DATA_SCRAPING)
4. [안드로이드 어플리케이션](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTON_DESIGN_ANDROID)
### 아티클

    서비스를 개발하면서 있었던 주요 이슈에 대해 정리한 글들입니다.

1. [추천 알고리즘 설계기](https://robinjoon.notion.site/81ea5ddd83f04e6eb81cdc16124c620f?pvs=4)
2. 잘못된 추상화의 폐해
3. 상품 인식 모듈 성능 개선기
4. [데이터 수집 모듈 성능 개선기](https://robinjoon.notion.site/25d0b94ca1394fc8a579d691d5dcd34a?pvs=4)
5. AWS 사용 실패기
