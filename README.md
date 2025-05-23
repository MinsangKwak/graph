# 🎯 JavaScript Chart CRUD with Table & JSON Editor

본 프로젝트는 순수 HTML, CSS, JavaScript만을 사용하여 그래프 데이터를 시각화하고,  
테이블 및 JSON 에디터를 통해 데이터를 직접 관리할 수 있는 UI 기능을 제공합니다.

-   바로가기: [페이지 보기](https://minsangkwak.github.io/graph/)

---

## 📌 기능 개요

### 📊 1. 그래프

-   수직 막대(bar) 차트로 데이터 시각화
-   데이터는 하단 라벨 기준(`ID`)으로 표시되며, Y축 범례(`0`, `100`) 고정

### ✏️ 2. 값 편집 (테이블)

-   초기 데이터 렌더링 후 삭제 가능
-   값은 `0~100` 사이의 숫자만 허용됨

### ➕ 3. 값 추가

-   사용자 입력을 통해 `ID`, `Value` 추가
-   중복된 ID 입력 시 경고 발생
-   입력된 값이 유효하지 않으면 alert 처리

### 🧾 4. 고급 편집 (JSON 기반)

-   전체 데이터를 JSON 형식으로 직접 수정
-   유효성 검사 포함 (`id`, `value`, 범위 체크)

---

## 🛠 기술 스택

| 항목   | 내용                             |
| ------ | -------------------------------- |
| 언어   | HTML5, CSS3, JavaScript (ES6)    |
| 시각화 | DOM 기반 수직 막대 그래프        |
| 접근성 | ARIA, hidden label 적용          |
| 디자인 | Pretendard 폰트, Custom 스타일링 |
| 반응형 | 가로 스크롤 대응 완비            |

---

## 📁 파일 구조

```
├── index.html
├── index.css
├── main.js
└── README.md
```

---

## 📷 UI 구성 미리보기

> ✅ 주요 특징:
>
> -   Y축은 고정된 상태에서, X축만 가로 스크롤 가능
> -   막대는 바닥에 정확히 붙어있고, 범례와 라벨도 겹치지 않음
> -   Bootstrap `floating label` 방식의 입력 인터페이스 구현

---

## 🚀 실행 방법

1. GitHub에서 소스코드 클론 또는 다운로드
2. 로컬에서 `index.html` 파일을 브라우저로 열기
3. 별도 빌드/서버 환경 없이 동작

---

## 📌 주요 제약 조건

-   `value`는 0~100까지만 허용되며, 벗어나는 입력은 alert 발생
-   입력값이 비어있거나 숫자가 아닌 경우도 추가/적용 불가

---

## 🙋‍♂️ 담당자

-   **곽민상**
-   GitHub: [@minsangkwak](https://github.com/MinsangKwak)

---

## 📄 라이선스

본 프로젝트는 과제 제출용이며, 자유롭게 사용 및 수정 가능합니다.
