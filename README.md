4CSoft – LX2 Home

토스 페이먼츠 스타일의 깔끔하고 모던한 UI/UX를 기반으로 설계된 LX2 학습관리시스템 소개 페이지입니다.
부드러운 인터랙션, 반응형 구성, 신뢰감 있는 컬러를 통해 직관적인 사용자 경험을 제공합니다.

🎨 디자인 특징

미니멀하고 현대적인 인터페이스
스크롤·페이드·호버 중심의 자연스러운 애니메이션
모바일·태블릿·데스크톱 완전 반응형
블루 기반의 신뢰감 있는 색상 팔레트
넓은 여백 중심의 가독성 높은 레이아웃

📁 프로젝트 구조
4csoft_homepage/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
└── README.md

🚀 시작하기
1. 클론
git clone [repository-url]
cd 4csoft_homepage

2. 로컬 실행
python -m http.server 8000
# 또는
npx serve
# 또는 VSCode Live Server

브라우저 접속: http://localhost:8000

📋 주요 기능
네비게이션
스크롤 시 헤더 그림자
부드러운 스크롤 이동
모바일 햄버거 메뉴
히어로 섹션
임팩트 있는 헤드라인
그라데이션 텍스트
3D 카드·페이드인 애니메이션
카운트업 효과
기능 탭
학습관리 / 교육관리 / 전문솔루션 / AI 기술
부드러운 탭 전환
카드 호버 효과
FAQ 섹션
아코디언 구조
부드러운 열림/닫힘 애니메이션
파트너 로고
그리드 정렬
로고 호버 인터랙션
문의·CTA
그라데이션 배경
명확한 CTA 버튼

🎯 인터랙션 요소
JavaScript
부드러운 스크롤
Intersection Observer 기반 페이드인
숫자 카운트업
탭 컨트롤
FAQ 아코디언
스크롤 진행 바
커서 트래킹 효과
CSS
버튼·카드 호버 애니메이션
텍스트·배경 그라데이션
백드롭 블러
3D 트랜스폼

🎨 색상 팔레트
Primary:   #0064FF
Secondary: #6366F1
Success:   #00D084
Gray:      #191F28 ~ #F9FAFB

📱 반응형 기준
모바일: 480px 이하
태블릿: 768px 이하
데스크톱: 1024px 이상

🔧 커스터마이징
:root {
    --primary: #0064FF;
    --secondary: #6366F1;
}

애니메이션 속도
--transition-fast: 150ms;
--transition-base: 250ms;
--transition-slow: 350ms;

📝 버전 정보
v1.0.0
초기 릴리스
토스 페이먼츠 스타일 UI 적용
반응형 + 인터랙션 기본 기능 구현
