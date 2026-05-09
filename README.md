# 26_1_SOFTWARE-ENGINEERING

## 👥 팀 정보
* **강의 정보:** 26_1 소프트웨어공학 2분반
* **조 번호:** 9조
* **팀 코드:** ` -- ` 

---

### 👤 [강신욱] (관리자 도메인 담당)
* **주요 역할:** 관리자 전용 설문 관리 및 통계 시스템 설계
* **상세 수행 내용:**
    * **Requirement List:** 설문 등록(6종 필수 데이터), 리스트 조회, 상세 정보 팝업, 삭제 및 통계 조회 기능 도출
    * **UI Design:** [Figma](https://www.figma.com/design/humQWwLh6EcrMXSs1sJ9dJ/%EC%9D%80%EC%86%8C%EA%B3%B5_UI?node-id=1-4&t=8eKC3QVjGrjK7h71-1)를 활용하여 관리자 대시보드, 등록 폼, 통계 카드 등 4종 화면 설계
    * **UML Modeling:** StarUML을 사용하여 `<<extend>>` 관계를 포함한 Use Case Diagram 작성 
    * **Use Case Description:** Actor-System 간 Step-by-step 상호작용 명세 작성

### 👤 [안예슬해] (회원 관리 도메인 담당)
* **주요 역할:** --
* **상세 수행 내용:**
    * **Requirement List:** 회원관리(회원가입,회원탈퇴,회원 로그인, 관리자 로그인,로그아웃)
    * **UI Design:** -- Figma를 활용하여 
    * **UML Modeling:** -- StarUML을 사용하여 `<<extend>>` 관계를 포함한 Use Case Diagram 작성 
    * **Use Case Description:** -- 

### 👤 [이성탁] (설문 참여 도메인 담당)
* **주요 역할:** 회원 설문 검색 및 응답 시스템 설계
* **상세 수행 내용:**
    * **Requirement List:** 설문 검색, 설문 정보 상세 조회, 설문 응답 기능 도출
    * **UI Design:** [Figma](https://www.figma.com/design/humQWwLh6EcrMXSs1sJ9dJ/%EC%9D%80%EC%86%8C%EA%B3%B5_UI?node-id=1-4&t=8eKC3QVjGrjK7h71-1)를 활용하여 설문 검색, 설문 정보 상세 조회, 설문 응답 3종 화면 설계
    * **UML Modeling:** StarUML을 사용하여 `<<extend>>` 관계를 포함한 Use Case Diagram 작성 
    * **Use Case Description:** Actor-System 간 Step-by-step 상호작용 명세 작성

---

## 📂 주요 산출물 (Project Artifacts)
1. **[Requirement_List.pdf]:** 기능적 요구사항 목록 및 팀 정보
2. **[UI_Design.pdf](https://www.figma.com/design/humQWwLh6EcrMXSs1sJ9dJ/%EC%9D%80%EC%86%8C%EA%B3%B5_UI?node-id=0-1&t=8eKC3QVjGrjK7h71-1):** 각 Use Case별 UI 설계 화면 (Figma)
3. **[Use_Case_Diagram.pdf]:** StarUML 기반 UML
4. **[Use_Case_Description.pdf]:** 단계별 상호작용 명세서
5. **log_output.txt:** Git Commit History 증빙 자료

---

## 💻 사용 기술 및 도구 (Tools)
* **Design:** [Figma](https://www.figma.com/)
* **Modeling:** [StarUML](https://staruml.io/)
* **Version Control:** Git, GitHub

---

## 📄 Git Log 추출 방법
아래 명령어를 통해 커밋 히스토리를 추출하였습니다.
```bash
git log --pretty="[%an] %cd %s %h" > log_output.txt
