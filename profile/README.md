# 편의점 할인 정보 통합 조회 서비스 : 편킹
>💡 편의점마다 다른 수많은 행사 상품.. 어디서 사는게 가장 저렴할까? 편킹에서 찾아봐야지~!
## 📱 어플리케이션 UI
<img src="https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/.github/blob/main/profile/%EC%95%B1%20%EC%A3%BC%EC%9A%94%20UI.png?raw=true" alt="어플리케이션 UI">

## 🚀핵심 기능
### 1️⃣ 추천 상품 목록
>💡 서비스 사용자의 행동을 분석해 `개인화된 추천 상품 목록`을 제공합니다!

### 2️⃣ 이미지 검색 기능(베타)
>💡 `상품의 사진`을 찍으면 해당 상품의 할인 정보를 제공합니다!

### 3️⃣ 동작 동영상
<center><img src="https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/.github/blob/main/profile/demo.gif?raw=true" width="30%" alt="동작 영상" loop = ></center>

## 🛠️ 시스템 구성 모듈
### 🧩시스템 구성 모듈 다이어그램
<img src="https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/.github/blob/main/profile/system_diagram.png?raw=true" alt="시스템 다이어그램">

### 📱 안드로이드 어플리케이션
>사용자에게 직접 제공되는 프로그램으로 적절한 UI를 구현하고 비즈니스 로직 서버와 통신을 수행합니다.
> 
>[![GitHub](https://img.shields.io/badge/GitHub_Repository-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTON_DESIGN_ANDROID)

### 👨‍💼 비즈니스 로직 서버
>추천 목록 기능을 비롯한 여러 기능을 위해 데이터베이스를 관리하고, 여러 로직을 구현하고 있는 모듈입니다.
> 
>[![GitHub](https://img.shields.io/badge/GitHub_Repository-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTONE_DESIGN_BackEnd_API_Server)
### 🤖 상품 인식 모듈(=이미지 인식 모듈)
>이미지 검색을 위해 상품의 이미지를 AI 를 통해 분석해 상품의 이름을 출력하는 모듈입니다.
> 
>[![GitHub](https://img.shields.io/badge/GitHub_Repository-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTONE_DESIGN_AI_Module)
### 💾 데이터 수집 모듈
>비즈니스 로직 서버가 활용할 수 있도록 상품 할인 정보를 수집 및 가공해 데이터를 제공하는 모듈입니다.
> 
>[![GitHub](https://img.shields.io/badge/GitHub_Repository-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HongikUniv-CAPSTONE-DESIGN-2023-YDY-1/CAPSTONE_DESIGN_BackEnd_DATA_SCRAPING)
## 📝 블로그
>서비스를 개발하면서 있었던 주요 이슈에 대해 정리한 글들입니다.

1. [편의점 할인 정보 모아보기 라는 주제를 정하기까지 있었던 일](https://robinjoon.notion.site/599b75adbbbf40a78904067af52c2775?pvs=4)
2. [추천 알고리즘 설계기](https://robinjoon.notion.site/81ea5ddd83f04e6eb81cdc16124c620f?pvs=4)
3. [상품 인식 모듈 성능 개선기](https://robinjoon.notion.site/c234ada4cf0748768a6836648de5b31c?pvs=4)
4. [데이터 수집 모듈 성능 개선기](https://robinjoon.notion.site/25d0b94ca1394fc8a579d691d5dcd34a?pvs=4)
5. [홍익대학교 소프트웨어융합학과 학술제 발표자료](https://drive.google.com/file/d/1mp1IOnpVBGewhU8-7EM9_uh1Bzj8YbDF/view?usp=sharing)
## 리크루팅
> 함께 프로젝트를 더욱 고도화 하여 `런칭 및 운영`을 하실 팀원을 모집합니다! 자세한 사항은 아래 노션에서 확인해주세요!!
> 
> [리크루팅](https://robinjoon.notion.site/54f8498f9b09428ea4f2d3383b0dc741?pvs=4)