# hodu-project
프로젝트 랜딩페이지
# HODU 웹페이지 프로젝트

![hodu-preview](./image/box-cat.png) <!-- 필요시 썸네일 이미지로 교체 -->

## 🐾 소개

HODU는 HTML과 CSS로 제작된 반응형 웹페이지입니다.  
간단한 소개, 이미지 갤러리, 블로그 구독 폼, 플로팅 버튼 등을 포함하고 있으며  
PC/모바일 화면에서 모두 잘 작동하도록 구성되어 있습니다.

## 📁 폴더 구조
```
📦 HODU/
├── index.html
├── reset.css
├── style.css
├── image/
│ ├── logo.svg
│ ├── menu.svg
│ ├── box-cat.png
│ ├── img_1.jpg
│ ├── img_2.jpg
│ ├── img_3.jpg
│ ├── img_4.jpg
│ ├── img_5.jpg
│ ├── mail.svg
│ ├── blog.svg
│ ├── instagram.svg
│ ├── facebook.svg
│ ├── youtube.svg
│ └── top-btn.svg

```

## ✨ 주요 기능

- 반응형 네비게이션 바 (`mobile-only`, `pc-only` 클래스 사용)
- 소개 섹션 및 다운로드 버튼
- 이미지 갤러리 및 설명 영역
- 블로그 구독 폼 (이메일 입력 필드 + 버튼)
- 플로팅 버튼 (상단 이동)
- 팝업 다이얼로그 (`<dialog>` 태그 사용)

## 🛠 사용 기술

- **HTML5**
- **CSS3**
  - Flexbox
  - 반응형 레이아웃 클래스
- (향후 JavaScript로 모달 및 메뉴 인터랙션 추가 예정)

## 📱 반응형 지원

모바일 및 데스크탑 해상도에서 최적화된 뷰를 제공합니다.  
모바일용 메뉴 버튼과 줄바꿈 클래스(`mobile-br`)로 모바일 친화적 구조를 적용했습니다.

## ✅ 접근성 고려 요소

- 의미 있는 시맨틱 태그 사용 (`header`, `main`, `section`, `footer` 등)
- 모든 이미지에 `alt` 속성 포함
- `aria-label`, `hidden` 클래스 등을 활용한 접근성 개선 구조

## 💡 향후 개선 아이디어

- 메뉴 버튼 클릭 시 JavaScript로 모바일 메뉴 토글 기능 추가
- 구독 폼에 유효성 검사 및 이메일 전송 처리 연동
- 모달(dialog) 동작 제어 JS 코드 추가
- 애니메이션 또는 인터랙션 향상 (예: 버튼 hover, 슬라이드 등)

