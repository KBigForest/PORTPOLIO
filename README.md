## [프로젝트] PORTFOLIO
---
### 목차
#### 1. [프로젝트 소개](#프로젝트-소개)
> (1) 기획의도 및 목적<br>
> (2) 멤버구성 및 역할<br>
> (3) 개발 기간<br>
> (4) 개발 방향성 및 범위<br>
> (5) 필요 기술 스택 및 개발 환경<br>
#### 2. [프로젝트 세부내용](#프로젝트-세부내용)
> (1) 구현 기능<br>
> (2) 배운점 & 아쉬운 점<br>
> (3) 이후의 계획
---
<br>

### 프로젝트 소개

#### (1) 기획의도 및 목적
* 해당 포트폴리오를 작성하고 개선점을 반영하여 자기PR이 가능한 포트폴리오 완성 

#### (2) 멤버구성
본인(1명): 기획 및 포트폴리오 작성 

#### (3) 개발 기간
23.04.16 - 23.04.30

#### (4) 개발 방향성 및 범위
* 플라스크를 활용 포트폴리오 작성
* 네비게이션 기능 확보, 상세보기 등 다양한 기능을 통한 가시성 및 사용자 편의 반영

#### (5) 필요 기술 스택
- Environment<br><img src="https://img.shields.io/badge/windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"/><br><img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
- Development
  * tkinter
  * beautifulsoup
  * flask
  * html/css
  * js(chatgpt 활용)
+ 시멘틱 코드(실제 도입하지는 않았지만 약간의 개념 이해)

---
### 프로젝트 세부내용

#### (1) [구현 기능](#구현-기능)
**해당 기능은 모두 
모바일 버전의 호환성을 고려함**
 * floating-sidebar
    - 각 주요 경험 파트와 프로젝트로 바로 이동
    - 초기안 : 직관적이지 않다는 피드백
   
    <img src="https://user-images.githubusercontent.com/99776305/235339000-f2f53ea4-b10c-4237-8fc3-387de3b0e27d.png" width="10%" height="5%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img> 
    - 개선안
    
    <img src="https://user-images.githubusercontent.com/99776305/235339086-44054cc0-f41a-41d9-bf35-4a041eb88db9.png" width="10%" height="5%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
    - 현재 프로젝트가 모바일 환경에서 한 버튼 안에 표시되지 않는 오류 : line-height를 적절히 조절하여 해결
    - SPAN태그를 활용해서 웹환경에서는 마우스를 올려놓았을 경우 나타나게 하는 기능 구현
    - 버튼의 경우 올려놓을 경우 색상이 변경되게 함(hover)
    
    <img width="120" alt="image" src="https://user-images.githubusercontent.com/99776305/235339149-c031aeb6-d821-4fc0-90e9-64ed059f121d.png">
    
  * 네비게이션 바
    - 메인 로고 / 각 파트 + 프로젝트의 경우 중요하기 때문에 다른 버튼 디자인 사용
    - 버튼의 경우 올려놓을 경우 색상이 변경되게 함(hover)
   <img width="938" alt="image" src="https://user-images.githubusercontent.com/99776305/235338129-ea3cce53-3fd8-419b-a82d-079c1555786a.png">
    
    
  * 메인화면(content-box)
    - 기본 사진
    - 간단한 자기소개
    - 약력 제시
    
  * summary 파트 & SOFT SKILL 파트
    - 주요한 경험 및 실적은 강조
    
  * HARD SKILL 파트
    - js를 통해 각 요소 skill요소들이 숨길 수 있도록 구혀
    - 피드백 : hard skill 중에서도 tool활용법과 기술 스택을 구분 지을 팔요 표현하는 것이 바람직.(추후 수정 예정)
  
  * experience 파트
    - 중요 주제 및 제목, 날짜는 보이게 하고 원할 시 확인 가능하게 하는 상세보기 제공
  
  * 프로젝트 파트
   - poloroid 느낌으로 제작
   - 틀 안에 사진과 내용을 적을 수 있는 칸 마
    
#### (2) [배운점 & 아쉬운 점](#배운점-&-아쉬운-점)
  * 아주 기초적인 폼플렛을 활용한 점에서 아쉬웠음.
  * 다른 라이브러리를 배우고 활용해서 제작하고 싶음.
#### (3) [이후의 계획](#이후의-계획)
  * 추후 추천사 및 방명록 기능 마련


